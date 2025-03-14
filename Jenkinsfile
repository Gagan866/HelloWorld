pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Gagan866/HelloWorld.git/HelloWorld.git'
            }
        }

        stage('Compile Java') {
            steps {
                bat '"C:\\Program Files\\Java\\jdk-21\\bin\\javac" HelloWorld.java'
            }
        }

        stage('Run Java Application') {
            steps {
                bat '"C:\\Program Files\\Java\\jdk-21\\bin\\java" HelloWorld'
            }
        }
    }
}
