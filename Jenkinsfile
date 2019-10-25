pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Welcome Here!'
        sh mkdir test
       }
      
    }
  }
  
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
