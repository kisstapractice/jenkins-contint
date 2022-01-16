pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is KissKiralyTamas'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production for me') {
                  steps {
                        echo "Deploying in Production Area 4 KissTamas"
                  }
            }
      }
}
