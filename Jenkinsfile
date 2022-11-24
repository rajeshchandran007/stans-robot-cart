pipeline{
    agent any 
    stages {
        stage('Lint Checks') {
            steps {
                sh "npm install jslint"   
                sh "~/node_modules/jslint/bin/jslint.js server.js"
            }
        } 
        stage('Code Quality Checks') {
            steps {
                sh "echo SonarChecksInProgress"   

            }
        }     

    }   // end of stages 
}  // end of pipelines