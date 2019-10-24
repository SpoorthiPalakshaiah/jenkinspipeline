pipeline {
    agent any
tools { 
        jdk 'jdk8' 
    }
stages{
        stage('Build'){
            steps {
               echo 'Building....'
            }
            post {
                success {
                    echo 'Now Archiving...'
                }
            }
        }
    }
}
