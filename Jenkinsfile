node{
 stage('checkout'){
 sh 'echo "checkout"'
  checkout scm
 sh 'ls /var/jenkins_home/workspace/sample2_main'
 sh 'cd /var/jenkins_home/workspace/sample2_main/ccode && make'
 }
 stage('build'){
 sh 'echo "Build"'
 }
 }
