pipeline{
    agent{
        label{
            label "dev"
        }
    }
    stages{
        
        stage('Git'){
            steps{
            git branch: 'main', url: 'https://github.com/GARAGANAGARAJU/helloworldapp.git'
            }
        }
        stage('Buildl'){
            steps{
                sh 'mvn clean install package'
            }
        }
    }
}
