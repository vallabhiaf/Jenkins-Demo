pipeline {
         agent any
         triggers {
       //poll repo every 2 minute for changes in git 
                  pollSCM('*/2 * * * *')}
         
         stages {
                 stage('Run') {
                 steps {
                     sh "docker --version"
                     sh "sudo docker build -t jenkins-demo ."
                 }
                 }}}
