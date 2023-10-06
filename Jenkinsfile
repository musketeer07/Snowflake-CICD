pipeline {
agent any
stages {
    stage("Git checkout") {
        steps {
            git 'https://github.com/musketeer07/Snowflake-CICD.git'
        }
    }

    stage("Postsonar") {
        steps{
            bat 'echo "All done"'
      }
    }
  }
}
