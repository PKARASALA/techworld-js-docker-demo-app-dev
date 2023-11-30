pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'master', url: 'https://github.com/PKARASALA/techworld-js-docker-demo-app-dev.git'
                }
            }
        }

        stage('build') {
            
            steps {

                echo 'building application..'
            }
        }

        stage('test'){
            
            steps{

                echo 'Testing application..'
            }
        }

        stage('deploy') {

            steps {
                echo 'Testing application..'

            }
        }

    }
}
}