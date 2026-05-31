pipeline {
    agent any 
    stages {
        stage ("build") {
            agent {
                label "java-slave"
            }
            steps {
                echo "build stage"
                sh "hostname -i"
            }
        }
        stage ("sonar") {
            steps {
                echo "sonar stage"
                sh "hostname -i"
                
            }
        }
        stage ("docker") {
            steps {
                echo "docker stage"
            }
        }
        stage ("docker image build and push") {
            steps {
                echo "dockerbuild stage"
            }
        }
    }
}
