pipeline{
    agent{
        label{
            label "dev"
        }
    }
    stages{
        
        stage('Git'){
            steps{
            
            }
        }
        stage('Build'){
            steps{
                sh 'mvn clean install package'
            }
        }
    }
}
