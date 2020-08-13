pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                g++ -o main.cpp
            }
            steps {
                ls
                ./a.exe
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Clean') {
            steps {
                rm ./a.exe
            }
        }
    }
    
    /*
    node {
        // triggers the checkout of the current git commit that triggered the pipeline (webhook)
        checkout scm 
        // .. snip ..
    }
    */
}