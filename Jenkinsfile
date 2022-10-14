pipeline {
    agent{
        docker {
            image 'salesforce/salesforcedx'
        }    
    } 
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
