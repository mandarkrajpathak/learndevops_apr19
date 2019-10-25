pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Welcome Here!'
       }
      steps{dir}
      steps{ls}
    }
  }
  
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
