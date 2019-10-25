pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Welcome Here!'
        dir
        ls
      }
    }
  }
  
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
