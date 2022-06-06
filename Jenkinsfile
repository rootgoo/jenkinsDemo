pipeline {
    agent {
        label "demoAgent"   
    }
    stages {         
        stage('Time') {
            steps {
                echo '20200607'
            }
        }
    }
    post{
        always '20200606'
    }
}
