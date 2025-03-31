pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the public Git repository
                git url: 'https://github.com/Shub2610/Java_Assignment.git'
            }
        }
        
        stage('Compile') {
            steps {
                // Compile the Java code
                bat 'javac Hello.java'
            }
        }
        
        stage('Run') {
            steps {
                // Run the compiled Java program
                bat 'java Hello'
            }
        }
    }
}
