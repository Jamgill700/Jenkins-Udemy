pipeline {
    agent any 
    stages {
        stage("Stage 1") {
            steps {
                    sh 'pwsh --version'
            }
        }
        stage("Stage 2") {
            steps {
                    echo "This is stage 2"
                    sh 'pwsh test.ps1'
            }
        }
        stage("Stage 3") {
            steps {
                    echo "This is stage 3"
            }
        }
        stage("Stage 4") {
            steps {
                    echo "This is stage 4"
                }
        }
        stage("Stage 5") {
            steps {
                    echo "This is stage 5"
            }
        }
    }
}
