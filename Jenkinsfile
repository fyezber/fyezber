pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
	  
stage ('build') {
  echo 'Build stage'
}
stage ('test: integration-&-quality') {
  echo 'quality stage'
}

stage ('deploy:prod') {
  echo 'Deploy stage'
}
   }
}
