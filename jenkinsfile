pipeline {
    agent any
    environment {
        DEPLOY_SERVER = '13.201.68.212'
        DEPLOY_USER = 'ubuntu'
        DEPLOY_PATH = '/var/www/html'
    }
    stages {
        stage('Deploy') {
            steps {
                git branch: 'main', url: 'https://github.com/agowtham659-dev/go-repo.git'
		credentialsId: 'github-pat'
                sh 'mkdir -p build && cp -r index.html src build/'
                sshagent(['-----BEGIN OPENSSH PRIVATE KEY-----
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
-----END OPENSSH PRIVATE KEY-----']) {
                    sh """
                        rsync -avz --delete build/ ${DEPLOY_USER}@${DEPLOY_SERVER}:${DEPLOY_PATH}/
                        ssh ${DEPLOY_USER}@${DEPLOY_SERVER} 'sudo chown -R www-data:www-data ${DEPLOY_PATH}'
                    """
                }
                sh "curl -s -o /dev/null -w '%{http_code}' http://${DEPLOY_SERVER} | grep -q 200 || exit 1"
            }
        }
    }
}
