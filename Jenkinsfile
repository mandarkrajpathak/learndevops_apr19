pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        rmdir 20191019
        mkdir 20191019
        echo "Welcome Here!" > 20191019.txt

      }
    }
  }
  
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
