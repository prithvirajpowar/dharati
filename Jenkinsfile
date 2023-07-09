pipeline {
    agent any
    stages {
        stage('Build APK') {
            steps {
                sh 'flutter pub get'
                sh 'flutter build apk'
            }
        }
    }
}
