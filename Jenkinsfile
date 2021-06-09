pipeline {
    agent any
    parameters {
        choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
    }
    stages {
        stage('Build') {
            steps {
                echo "Choice: ${params.CHOICE}"
            }
        }
    }
}
