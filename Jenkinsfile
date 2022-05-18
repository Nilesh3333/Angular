pipeline {
    agent any
    environment {
        PROJECT_ID = 'bonusquestion'
    }
    stages {
        stage("Checkout code") {
            steps {
                checkout scm
            }
        }
        stage('BuildAngular') {
            steps {
       
                    
					sh 'ng build'
           
            }
        }
        
    }    
}
