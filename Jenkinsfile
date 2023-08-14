pipeline {
  agent any
  tools {
    maven 'mavenTool'
    jdk 'openjdk11'
    jdk 'openjdk8'
  }
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
