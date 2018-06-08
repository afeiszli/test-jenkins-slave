node{
    stage('Checkout'){
        checkout scm
        sh 'echo env.GIT_BRANCH'
        sh 'echo ${GIT_BRANCH}'
        sh 'echo env.BRANCH_NAME'
        sh 'echo ${BRANCH_NAME}'
    }    
    stage('test'){
        sh 'echo env.GIT_BRANCH'
        sh 'echo ${GIT_BRANCH}'
        sh 'echo env.BRANCH_NAME'
        sh 'echo ${BRANCH_NAME}'
        sh 'printenv'
    }
}
