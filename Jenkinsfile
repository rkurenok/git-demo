node { 

    stage('Clone git') {
        echo '-----Cloning GIT...-----'
    
	git 'https://github.com/rkurenok/git-demo.git'
    }
     

    /*stage('install node_modules') {
        echo '-----install node_modules-----'
        bat 'npm install'
    }
    stage('Test') {
        echo '-----TEST-----'
        bat 'npm helloworld.js'
    }*/

    node helloworld.js

    stage('Test') {
        echo 'Test'
        bat 'node helloworld.js'
    }

}