pipeline {

    agent any
    
    stages {
    
        stage("build") {
        
            steps {
                echo 'Building the application.....'
                bat "npm install"
            }
           
        }
        
          stage("test") {
        
            steps {
                echo 'Testing the application.....'
            }
           
        }
        
          stage("deploy") {
        
            steps {
                echo 'Deploying the application.....'
            
            }
           
        }
        
    }
}
