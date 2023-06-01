node {
    stage('Postman CI Demo'){
        git 'https://github.com/ARQ-SudipPoudel/postman-CI-demo.git'
    }
    stage('Install node dependencies'){
         sh 'npm install'
     }
     stage('Run Postman Tests'){
        sh 'npm run api-tests'   
     }
}
