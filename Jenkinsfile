pipeline {
agent any
stages {
    stage("Git checkout") {
        steps {
            deleteDir()
            git branch: 'main', url: 'https://github.com/musketeer07/Snowflake-CICD.git'
        }
    }
    
    stage("View files"){
        steps{
            script{
                sh "ls -l"
            }
        }
    }
  }
}


