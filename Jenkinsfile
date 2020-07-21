pipeline { 
    agent any
    stages {
        stage('SCM') { 
            steps { 
                git changelog: false, poll: false, url: 'https://github.com/vasu7github/SampleWebApp.git' 
            }
        }
   }
}
