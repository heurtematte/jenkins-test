
pipeline {
    agent any
    environment {
        HOME = "${env.WORKSPACE}"
    }
    stages {
        stage('build') {
            steps {
                script {
                    sh """
                        #!/usr/bin/env bash
                        set -euo pipefail

                        set -x && printenv
                    """
                }
            }
        }
    }
    
}

