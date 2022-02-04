
pipeline {
    agent any

    stages {
        
        stage('Stage 1') {
            steps {
                sh ''' 
                    docker build -it nodejs:lts .
                    docker run -p 3000:3000 nodejs:lts
                '''
            }
        }
        
    }
}
