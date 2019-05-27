
node{
   stage('SCM checkout'){
     git 'git@github.com:linuxacademy/cicd-pipeline-train-schedule-git.git'
   }
   stage('Compile Package){
     sh 'mvn package'
   }

}
