pipeline {
    agent {
        docker {
            image 'maven:3-alpine'
            args '-v //C/Users/LeBattant/.m2/://home/.m2/'  
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'   
            }
        }
    }
}




