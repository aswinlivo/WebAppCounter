pipeline {
  
  agent { lable 'master' }
    
  stages {
	  stage("from git") {
		steps{
		echo "am from git"
		}
	  }
	  stage(" build by maven") {
		steps{
		 echo "am building"	
		}
	  }
	  stage("result") {
		steps{
		echo "this is the result stage"
		}
	  }
  
  }
}