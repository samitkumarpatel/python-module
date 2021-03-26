pipeline {
    agent {
        label 'python'
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