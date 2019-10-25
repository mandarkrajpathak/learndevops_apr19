pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Welcome Here!'
        CD C:/CarPro/Temp
        mkdir Test
      }
    }
  }
  
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
