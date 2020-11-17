node{
 stage('checkout'){
 sh 'echo "checkout"'
 checkout scm
 
 }
 stage('build'){
 sh 'ls /var/jenkins_home/workspace/sample2_main'
 sh 'cd /var/jenkins_home/workspace/sample2_main/ccode && make && chmod + hellomake'
 }
 stage('test'){
  sh './hellomake'
 }
