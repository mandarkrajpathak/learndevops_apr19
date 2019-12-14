pipeline {
  agent AWSCarpro
  stages {
    stage('build') {
      steps {
        echo 'Welcome Here!'
        bat """
        mkdir TEST1       
        """
        copy dstFile: 'C:\\CarProInstallation\\', srcFile: 'C:\\Users\\Jenkins\\.ssh\\workspace\\NewTestProject_master'
        }
    }
    
    stage('Example') {
            input {
                message "Should we continue?"
                ok "Yes, we should."
                submitter "alice,bob"
                parameters {
                    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
            }
            steps {
                echo "Hello, ${PERSON}, nice to meet you."
            }
        }
  }
  
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
