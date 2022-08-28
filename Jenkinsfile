node {
  stage('Checkout SCM') {
    git branch:'main', url:'https://github.com/subbuto/hello-world-2.git'
  }
  stage('Install node modules') {
    echo "npm install"
  }
  stage('test') {
    echo "npm run test-headless"
  }
  stage('Build') {
    echo "npm run build --prod"
  }
  stage('Copy') {
    echo "cp -a /var/lib/jenkins/angular pipeline/dist/hello-world-2/. /var/www/hello-world-2/html"
  }
}
