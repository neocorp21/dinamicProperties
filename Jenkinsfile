pipeline {
    agent any
    stages {
        
        stage('Checkout') {
            steps {
                script {
                    echo "Clonando el repositorio..."
                   
                }
            }
        }
        stage('Build') {
            steps {
                script {
                    echo "Estado del repositorio:"
                    sh 'git status'  // Este paso nos permitirá ver si git reconoce el repositorio
                }
            }
        }
    }
}
