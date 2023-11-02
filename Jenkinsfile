pipeline {
  agent { label param.'agent01'}

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

  }
}
