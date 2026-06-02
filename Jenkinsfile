pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                cccc
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
