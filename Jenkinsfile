pipeline {
    agent{
        docker {
            image 'salesforce/salesforcedx'
            label 'sfdx'
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
