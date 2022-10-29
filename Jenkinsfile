//Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent  any   
    stages {
        stage('build') {
            steps {
                withMaven(maven : 'MAVEN') {
                bat'mvn clean package'
            }
        }
    }
}
}
