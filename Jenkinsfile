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
                echo 'ทดสอบผ่านแล้ว แต่ยังไม่ได้กำหนดคำสั่ง deploy จริง'
            }
        }
    }
}
