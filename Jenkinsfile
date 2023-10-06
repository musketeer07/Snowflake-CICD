pipeline{
  agent any

  stages{
    stage('Checkout Code'){
      steps{
        git 'https://github.com/musketeer07/Snowflake-CICD.git'
        script{
          sh 'ls -l'
        }
      }
    } 
  }
}
