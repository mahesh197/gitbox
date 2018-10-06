node {
   def mvnHome
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/mahesh197/gitbox.git'
   }
   stage('Build') {
    echo "Building started"
    echo "Building done"
   }
   stage('Results') {
     echo "email start....."
     build job :"BuildJob"
     echo "email done"
   }
}
