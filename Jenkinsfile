/* Requires the Docker Pipeline plugin */
pipeline {

    agent any 
    // { 
    //     docker { 
    //         image 'python:3.12.1-alpine3.19' 
    //     } 
    // }

    stages {
        stage('build') {
            steps {
                script (
                    bat 'python main.py'
                )
            }
        }
    }
    
}