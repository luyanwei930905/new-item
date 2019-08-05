pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1') {
          steps {
            sh '''node {  
    stage(\'Build\') { 
        // 
    }
    stage(\'Test\') { 
        // 
    }
    stage(\'Deploy\') { 
        // 
    }
}'''
          }
        }
        stage('branch1') {
          steps {
            sh '''node {  
    stage(\'Build\') { 
        // 
    }
    stage(\'Test\') { 
        // 
    }
    stage(\'Deploy\') { 
        // 
    }
}'''
          }
        }
      }
    }
  }
}