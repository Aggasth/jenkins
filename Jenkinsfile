pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        echo '¡Bienvenido! Comienza la ejecución'
      }
    }
    stage('Ejecutar Calculadora') {
      steps {
        script {
          mvn test
        }
      }
    }
    stage('Verificacion') {
      steps {
        echo 'Ejecutado correctamente!'
      }
    }
  }
}
