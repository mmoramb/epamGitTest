pipeline {
    agent any
    parameters{
        choice(name:'CHOICE', choices:['Maven', 'Gradle'], description: 'Choose one')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello first module  ${params.CHOICE}"'
            }
        }
    }
}
