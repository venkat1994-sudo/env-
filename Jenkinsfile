pipeline {
    agent any
    environment{
        name1 = "jeff"
        name2 = "john"
    }
    
    stages {
        stage('Build'){
            environment {
                name2 = "mike"
                name3 = "jamie"
            }
            steps {
                echo "name1 ${name1}"
                echo "name2 ${name2}"
                ehco "name3 ${name3}"
                sh "printenv"
              
            }
            }
        stage('Test'){
            steps{
            echo "name2 ${name2}"
            }
        }
            
    }
        
}
