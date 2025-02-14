pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main' url: 'https://github.com/Haritha-mekala/java-war-repo.git'
                
            }
        }
        stage('Build') {
            steps {
                 sh 'mvn clean install'  
    
            }
        }
    }
}
