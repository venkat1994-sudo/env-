pipeline {
    agent any
    environment{
        name1 = "venkat"
        name2 = "ashita"
    }
    
    stages {
        stage('Build'){
            environment {
                name3 = "venkatesh"
            }
            steps {
                echo "name1 ${name1}"
            }
            }
        stage('Test'){
            steps{
            echo "name2 ${name3}"
            }
        }
            
        
    }
