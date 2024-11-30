
pipeline {
    agent any
    stages{
        stage('Git access'){
            steps{
                git branch : 'main' ,url :'https://github.com/donthigarivinay/week4.git'
            }
        }

        stage('Java execution'){
            steps{
                bat 'javac code.java'
                bat 'java code'
            }
        }
        stage('Python execution'){
            steps{
               bat 'C:\\windows\\py.exe code.py'
            }
        }
    }
}
