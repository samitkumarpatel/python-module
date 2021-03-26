pipeline {
    agent {
        label 'pyhton'
    }
    stages {
        stage('test module') {
            sh """
                ls -al
                python main_program.py
            """
        }
    }
}