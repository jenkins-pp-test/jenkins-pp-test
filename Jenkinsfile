pipeline {
    agent {
        node { label "master" }
    }
    stages {
        stage('Pull Git Demo') {
            steps{
                //拉取代码
                echo "Prepare Git Code"
                git 'git@github.com:jenkins-pp-test/jenkins-pp-test.git'
                echo 'Preparing end..'
            }
        }
        stage('Build1') { 
            steps {
                //执行构建命令
                echo 'Build1 Stage starting...'
                sleep 5
                echo 'Build1 Stage end...'
            }
        }
        stage('Build2') {
            steps  {
                echo 'Build2 Stage starting...'
                sleep 5
                echo 'Build2 Stage end...'
            }
        }

        stage('Compile') {
            steps  {
                echo 'Compile Stage'
            }
        }
        stage('Test') {
            steps  {
                echo 'Test Stage'
            }
        }
        stage('Deploy') {
            steps  {
                echo 'Deploy Stage'
            }
        }
        stage('Integrate') {
            steps  {
                echo 'Integrate Stage'
            }
        }


    }
}
