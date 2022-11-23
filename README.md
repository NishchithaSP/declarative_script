# declarative_script

pipeline {
    agent any

    stages {
        stage('Git Clone') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
