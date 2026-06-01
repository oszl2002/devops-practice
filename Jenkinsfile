pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Build Success'
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
