pipeline {
    agent any
    stages {
          stage ("Build") {

                steps{
                    withMaven() {
                        sh "./mvnw verify"
                    }   
                }
            }
            stage ("Deploy to CloudFoundry") {
                    
                steps {
                    echo 'fake deploy'
                }
            }      
    }
}
