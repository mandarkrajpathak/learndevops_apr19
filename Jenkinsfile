pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Welcome Here!'
        echo get_current_time_date()
       }
      
    }
  }
  
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
