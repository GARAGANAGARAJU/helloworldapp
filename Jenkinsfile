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
        stage('Build'){
            steps{
                sh 'mvn clean install package'
                sh "mv target/*.war target/myweb.war"
            }
        }
    }
}
