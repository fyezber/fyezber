pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
	  
	stage ('build') {
	  steps {
	    echo 'Build stage'
	  }
	}
	stage ('test: integration-&-quality') {
	   steps {
	     echo 'quality stage'
	  }
	}

	stage ('deploy') {
	  steps {
	     echo 'quality stage'
	    }
	  }
    }
}
