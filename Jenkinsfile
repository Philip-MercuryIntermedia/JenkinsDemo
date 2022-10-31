pipeline {
  
  agent any
  
  stages {
    stage("build") {
      steps {
        echo "Project is Building"
      }
    }
    stage("test") {
      steps {
        echo "Project is Testing"
      }
    }
    stage("deploying") {
      steps {
        echo "Project is Deploying"
      }
    }
  }
  post {
    always {
      echo " trigger always"
    }
  }
}
