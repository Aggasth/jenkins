pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        echo '¡Bienvenido! Comienza la ejecución'
      }
    }
    stage('Clonar Repositorio') {
      steps {
        git clone 'https://github.com/Aggasth/jenkins.git'
      }
    }
    stage('Ejecutar Calculadora') {
      steps {
        sh 'src/main/java/co/edu/ejemplo/calculadora/CalculadoraLogic.java'
      }
    }
    stage('Verificacion') {
      steps {
        echo 'Ejecutado correctamente!'
      }
    }
  }
}
