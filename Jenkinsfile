pipeline {
agent any
stages {
    stage("Git checkout") {
        steps {
            git 'https://github.com/AmolMandloi/junit-java-example.git'
        }
    }

    stage("Postsonar") {
        steps{
            bat 'echo "All done"'
      }
    }
  }
}
