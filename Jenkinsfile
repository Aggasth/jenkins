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
          mvn compile
          mvn test
        }
      }
    }
  }
}
