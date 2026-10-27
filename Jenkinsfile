pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'python --version'
            }
        }

        stage('Test') {
    steps {
        bat 'python -m pip install pytest'
        bat 'python -m pytest'
    }
}

        stage('Deploy') {
            steps {
                echo 'เพิ่มคำสั่ง deploy ของโปรเจกต์ภายหลัง'
            }
        }
    }
}
