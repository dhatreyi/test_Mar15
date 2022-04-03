pipeline {
  agen any
  stages {
    stage ('git checkout') {
      steps {
        echo "Checkout of source code from git -stage1"
        checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/dhatreyi/test_Mar15.git']]])
        
      }
    }
  }
}
