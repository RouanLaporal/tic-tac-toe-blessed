pipeline{
    agent any
    
    stages{
        stage('build'){
            steps{
                echo 'Building'
            }
            steps{
                npm run build
            }
            steps{
                echo 'Success'
            }
        }
    }
}
