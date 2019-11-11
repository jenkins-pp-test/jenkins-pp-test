pipeline {
    agent {
        node { label "master" }
    }
    stages {
        stage('Pull Git Demo') {
            steps{
                //拉取代码
                git 'git@github.com:rulai-qiangwei/jenkins-test.git'
            }
        }
        stage('Build1') { 
            steps {
                //执行构建命令
                echo 'Build1 Stage'
            }
        }
        stage('Build2') {
            steps  {
                echo 'Build2 Stage'
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
