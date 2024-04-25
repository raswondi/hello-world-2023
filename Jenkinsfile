pipeline {
    agent any
    tools{
      maven 'M2_Home'
    }
     stages{
      stage('Hello'){
       steps {
         echo "Hello World"
       }
    }
    
    stage("build"){
      steps {
        sh 'mvn clean'
      }
    }
    }

}
