pipeline {
    agent any

    stages {
        stage("deploy html site") {
            steps {
                echo publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, icon: '', keepAll: false, reportDir: '', reportFiles: 'registration.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])
            }
        }
    }
}
