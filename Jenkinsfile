pipeline {
    environment {
        PATH="/opt/apache-maven-3.9.8/bin/:$PATH"
    }
        stages {
        stage("biuld"){
            steps{
                sh 'mvn clean deploy'
            }
        }
         
    }
}
