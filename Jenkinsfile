pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                aaaa
            }
        }

        stage('Save File') {
            steps {
                writeFile file: 'result.txt', text: 'Build Success'
                sh 'cat result.txt'
            }
        }
    }
}
