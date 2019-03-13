pipeline {
  agent {
    dockerfile {
      filename 'Prueba'
    }

  }
  stages {
    stage('Ejecucion') {
      parallel {
        stage('Conexion') {
          steps {
            sh 'echo "Hola Mundo'
          }
        }
        stage('Bajando') {
          steps {
            echo 'Nuevo'
          }
        }
      }
    }
  }
  environment {
    Despliegue = ''
  }
}