pipeline {
  agent none
    stages {
        stage('Build') { 
          agent { label 'label1' }
            steps {
                echo "This is build stage"
            }
        }
        stage('Test') { 
          agent { label 'label1' }
            steps {
                echo "This is test stage"
            }
        }
        stage('Deploy') { 
          agent { label 'label1' }
            steps {
                echo "This is Deploy stage"
            }
        }
    }
}
