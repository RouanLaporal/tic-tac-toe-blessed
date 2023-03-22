pipeline{
    agent any
    
    stages{
        stage('build'){
            steps{
                echo 'Building'
                bat 'npm install && npm run build'
            }
        }
        stage('test'){
            steps{
                echo 'Testing'
                //sh 'npm test'
            }
        }
        stage('deploy'){
            steps{
                echo 'Deployment'
                //sh 'npm start'
            }
        }
    }
}
