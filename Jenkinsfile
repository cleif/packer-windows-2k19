pipeline {
  agent any
  stages {
    stage('print_message') {
      steps {
        echo 'First Step of packer-windows-2k19'
      }
    }

  }
    stage('pull from SCM'){
      steps{
        echo 'from source build packer data into artifact'
    }
  }
  environment {
    Dev = 'dev1'
  }
}