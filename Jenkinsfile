pipeline {
    agent any

    stages {
        stage('Build') {
            sh "ls"
            steps {
                echo 'Building..'
                // g++ -c main.cpp
                // g++ ./main.o -o main.exe
                // ./main.exe
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
            sh "ls"
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