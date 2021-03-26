pipeline {
    agent {
        label 'pyhton'
    }
    stages {
        stage('test module') {
            steps {
                sh """
                    ls -al
                    python main_program.py
                """
            }
           
        }
    }
}