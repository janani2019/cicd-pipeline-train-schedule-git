
node{
   stage('SCM checkout'){
      git 'https://github.com/janani2019/cicd-pipeline-train-schedule-git.git'
   }
   stage('Compile Package'){
      def mvnHome = tool name: 'maven', type: 'maven'      
      sh "${mvnHome}/bin/mvn package"
   }

   }
