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
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
			stage('Deploy in ambiente frillo') {
                  steps {
                        echo "Deploying in Ambiente frillo"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
			stage('Deploy alla brutto dio') {
                  steps {
                        echo "ALLA BRUTTO DIO"
                  }
            }
      }
}