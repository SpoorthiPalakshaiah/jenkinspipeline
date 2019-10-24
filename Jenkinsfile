pipeline {
    agent any

    triggers {
         pollSCM('* * * * *') // Polling Source Control
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
