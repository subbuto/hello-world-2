node {
  stage('Checkout SCM'){
    git branch: 'main', url: 'https://github.com/subbuto/hello-world-2.git'
  }
  stage('Install node modules'){
  sh "npm install"
  }
  stage('Build'){
    sh "npm run build:"
  }
  stage('Deploy'){
    sh "restart all"
