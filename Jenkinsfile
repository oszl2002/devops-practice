pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bbbb
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
