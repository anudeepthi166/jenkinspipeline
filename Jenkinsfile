pipeline{

agent any

stages{

	stage('SCM'){
		steps {
			 echo "git pull msg step1"
			  echo "git pull msg step2"
		}
	}
	stage('Deploy'){
		steps {
			 echo "code deploy msg"
		}
	}
	stage('Test'){
		steps {
			echo "Testing app msg"
		}
	}
	stage('Deploy to prod'){
		steps {
			echo "Final message"
		}
	}
	}
}
