pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Welcome Here!'
        mkdir /Carpro/Temp/Test
      }
    }
  }
  
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
