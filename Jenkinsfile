node{
stage('Checkout SCM'){
git branch: 'main', url: 'https://github.com/Tusharsharma225/FrontendMulti.git'
}

stage('Install node modules'){
bat "npm install -g @angular/cli"
}


stage('Build'){
bat "npm run build"
}

stage('Deploy'){
    bat "npm run ng serve"
 }
}
