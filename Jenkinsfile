pipeline {
    agent { label 'electronix' }

    stages {
        stage('Hello') { steps { echo "Hello jenkins" } }
        stage('Hello-Second'){ steps { echo "Hello Jenkin Second" } }
    }
}

post{
    success {
      echo "Pipeline Pass "
    }
    failure {
        echo "Pipeline Fail"
    }
}
