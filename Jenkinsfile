node { 

    stage('Clone git') {
        echo '-----Cloning GIT...-----'
    
	git 'https://github.com/rkurenok/git-demo.git'
    }
     


    stage('Test') {
        echo '-----TEST-----'
        bat 'npm helloworld.js'
    }

}