node{
    stage('Checkout SCM'){
        git branch: "master", url: "https://github.com/Thakurking/demo-angular.git"
    }

    stage('Install node modules'){
        sh "npm install"
    }

    stage('Test'){
        sh "npm run test"
    }
    
    stage('Build'){
        sh 'ng build'
    }
}