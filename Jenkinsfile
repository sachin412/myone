stages{
        stage('cleaning old code'){
            steps{
                sh '''
                rm -rf ${REPO_PATH}/jktyre_common_utilities/* && \
                cp -r * ${REPO_PATH}/jktyre_common_utilities/
                '''
            }
        }
