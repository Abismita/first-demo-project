pipeline{
    agent any
    tools{
        maven 'maven'
    }
        stage('build'){
            steps{
                sh 'mvn clean install'
            }
        }
    }
}
