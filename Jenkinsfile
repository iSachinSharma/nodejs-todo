pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Test') {
            steps {
                bat 'npm test'
            }
        }

        stage('Run Application') {
            steps {
                bat 'start cmd /c node index.js'
            }
        }
    }
<<<<<<< HEAD
}
=======
}
>>>>>>> ca2b35ad31cb434219d3630f110f3326f8e0231c
