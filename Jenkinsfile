
pipeline {
    agent any

    stages {
        
        stage('Stage 1') {
            steps {
                sh ''' 
                    docker build -t nodejs:lts .
                    docker run -d -p 3000:3000 nodejs:lts
                '''
            }
        }
        
    }
}
