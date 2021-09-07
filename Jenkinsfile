// Scipted type code
// declerative pipline
pipeline {
	//agent any
	agent { docker { image 'maven :3.6.3'}}
			stages {
				stage ('build'){
					steps {
					sh 'mvn --version'
					echo "Build"
					
				}
			}
			stage ('Test'){
					steps {
					echo "Test "
				}
			}
			stage ('Intgartion Test'){
					steps {
					echo "Intgartion test"
				}
			}
		}
		 post {
			always {
				echo ' I am always run'
			}
			success {
				echo 'I am success run'
			}

			failure {
				echo 'When you rae failing '
			}
		}
		

}
