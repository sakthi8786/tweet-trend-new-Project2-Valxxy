pipeline {
    agent any
        environment {
    PATH = "/opt/apache-maven-3.9.8/bin:$PATH"
            
    }
     stages {
        stage("build"){
            steps {
                 echo "----------- build started ----------"
                sh 'mvn --version'
                sh 'mvn clean deploy '
                 echo "----------- build complted ----------"
            }
        }
    } 
    
}
 
