node{
    stage('Checkout SCM'){
        git branch: "master", url: "https://github.com/Thakurking/demo-angular.git"
    }

    stage('Install node modules'){
        sh "npm install"
    }
    
    stage('Build'){
        sh 'ng build'
    }
}