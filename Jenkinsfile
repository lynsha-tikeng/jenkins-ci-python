pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/lynsha-tikeng/jenkins-ci-python.git'
            }
        }
        stage('Build') {
            steps { echo 'Simuler une construction du projet...' }
        }
        stage('Test') {
            steps { echo 'Simuler les tests du projet...' }
        }
    }
}
