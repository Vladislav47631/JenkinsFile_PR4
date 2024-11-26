pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Сборка приложения...' // Ваши шаги сборки
            }
        }
        // Добавьте другие стадии здесь
    }

    post {
        always {
            deleteDir()
        }
    }
}
