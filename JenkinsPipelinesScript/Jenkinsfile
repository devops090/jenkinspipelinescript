node{
    stage('clone the code'){
        echo "Downloading the code from github"
        git credentialsId: 'github_root', url: 'https://github.com/devops2k18/mavenrepo.git'
    }
    stage('clean'){
        echo "cleaning the code"
        sh 'mvn clean'
    }
     stage('compile'){
         echo "compiling the code"
        sh 'mvn compile'
    }
    stage('package'){
        echo "packaging the code"
        sh 'mvn package'
    }
    
    
    
}