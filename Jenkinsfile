pipeline {
    agent {
        docker {
            image 'my-jenkins-with-maven'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
