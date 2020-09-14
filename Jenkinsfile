pipeline {
  agent any
  stages {
    stage('st1') {
      steps {
        git 'https://github.com/asyousef/automated_junos_configuration_backup_on_git.git'
      }
    }

  }
  environment {
    VERSION = '20.1'
  }
}