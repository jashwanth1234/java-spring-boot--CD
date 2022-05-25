pipeline {
    agent any
    stages {
        stage ("Create Container") {
            steps {
                script {
                    sh """
                        docker run -d -p 9000:8080 springapp
                     """ 
                }
            }
        }
    }
}
