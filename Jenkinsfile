// Scipted type code
// declerative pipline
pipeline {
	agent any
			stages {
				stage ('build'){
					steps {
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
