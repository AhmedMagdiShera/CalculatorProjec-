pipeline {
    agent any
    triggers {
        cron('*/2 * * * *')
    }
    stages {
        stage('test') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Hello Sherra"
                    echo "bye bye"
                '''
            }
        }
    }
}
