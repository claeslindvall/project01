pipeline {
  agent { label params.'agent01'}

  stages {
    stage('Msg') {
      steps {
        echo 'Hepp'
      }
    }

    stage('Shell01') {
      steps {
        sh 'echo "Jabbado"'
      }
    }

    stage('Comple') {
      steps{
        sh 'cd demo; ./gradlew run'
        // sh 'echo $USER >> /tmp/user.fil'
      }
    }

  }
}
