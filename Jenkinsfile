pipeline {
         agent any
         triggers {
       // poll repo every 2 minute for changes
                  pollSCM('*/2 * * * *')}
         
         stages {
                 stage('Run') {
                 steps {
                     sh "docker --version"
                 }
                 }}}
