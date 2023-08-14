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
        git 'https://github.com/Aggasth/jenkins.git'
      }
    }
    stage('Ejecutar Calculadora') {
      steps {
        script {
          sh 'javac CalculadoraLogic.java'
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
