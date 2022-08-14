## Code quality check with sonarqube

### Start sonarqube server in beginning

Run following command to initiate sonarqube docker server.

`docker run -d --name sonarqube -p 9000:9000 sonarqube`

### Do a static code analysis before make a commit

Run following shel script and visit http://localhost:9000 ( login credentials `admin: test1234`) to see the results.

`sh sonar.sh`