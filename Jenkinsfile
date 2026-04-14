pipeline {
    agent any
    stages {
        stage('Build') { [cite: 392]
            steps {
                sh 'go build -o myapp main.go' [cite: 394, 398]
            }
        }
        stage('Test') { [cite: 401]
            steps {
                sh 'go test ./...' [cite: 415]
            }
        }
        stage('Deploy') { [cite: 421]
            steps {
                echo 'Artifact ready for deployment' [cite: 424, 428]
                // You can add 'sh "./myapp"' to simulate a run
            }
        }
    }
    post { [cite: 430]
        success {
            echo 'Pipeline executed successfully!' [cite: 431, 433]
        }
    }
}
