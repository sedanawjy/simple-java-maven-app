pipeline {
    agent any
    // image 'maven:3.9.3-eclipse-temurin-17-alpine' 
    // args '-v /root/.m2:/root/.m2' 
//    tools{
//        maven "Maven 3.6.3"
//    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
                //sh 'mvn -version'
            }
        }
    }
}


