pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // g++ -c main.cpp
                // g++ ./main.o -o main.exe
            }
            steps {
                ls
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
            steps {
                // rm ./main.o
                // rm ./main.exe
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