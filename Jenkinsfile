// Scipted type code
// declerative pipline
pipeline {
	agent any
	//agent { docker { image 'node:13.8'}}
			stages {
				stage ('build'){
					steps {
		
					echo "Build"
					echo " Build_Path  - $path"
					echo "Build_Number - $env.BUILD_NUMBER"
					echo "Build_Id  - $env.BUILD_ID"
					echo "Build_NAME  - $env.JOB_NAME"
					echo "Build_TAG - $env.BUILD_TAG"
					echo "Build_URL  - $env.BUILD_URL"
					
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
