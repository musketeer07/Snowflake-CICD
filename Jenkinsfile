pipeline{
  agent any

  stages{
    stage('Checkout Code'){
      steps{
        git 'https://github.com/musketeer07/Snowflake-CICD.git'
      }
    }


    stage('Display git repo'){
      steps{
        script{
          sh 'ls -l'
        }
      }
    }
  }
}
