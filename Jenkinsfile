pipeline{
  agent any

  stages{
    stage('Git Checkout'){
      steps{
        git 'https://github.com/musketeer07/Snowflake-CICD.git'
      }
    }

    stage('Hello World'){
      steps{
        echo 'Hello'
      }
    }
  }
}
