# SonarQube Docker Stack

1. Build and Run SonarQube docker-compose.yml with `docker-compose up -d`
2. Add this to your project docker-compose or just install sonar-scanner :
   > `sonar-scanner:`
   > `container_name: 'sonar_scanner'`
   > `image: sonarsource/sonar-scanner-cli`
   > `environment:`
   > `SONAR_HOST_URL: "http://${HOST_URL}"`
   > `volumes:`
   > `- ./www/phoenix:/usr/src`

3. Go to your SonarQube Host `http://${YOUR_HOST}:9001`
4. Create New Project
5. Run the sonar-scanner command in your website host

***

Retrouvez-moi sur [adriendudeck.online](http://adriendudeck.online)