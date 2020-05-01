pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Anshul from LevelUp360'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy in Staging') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy in Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}