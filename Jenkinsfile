node { 

    stage('Clone git') {
        echo '-----Cloning GIT...-----'
    
	git 'https://github.com/rkurenok/git-demo.git'
    }
     

    /*stage('install node_modules') {
        echo '-----install node_modules-----'
        bat 'npm install'
    }
    /*stage('Test') {
        echo '-----TEST-----'
        bat 'npm test'
    }*/
    
    stage('Helloworld') {
        echo '-----TEST-----'
        bat 'npm run test'
    }
    stage('ForJS') {
        echo '-----Test-----'
        bat 'npm run test1'
    }
}