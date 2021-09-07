
pipeline {
agent {
    docker {
        image 'maven:3.8.1-adoptopenjdk-11'
        args  '-v /tmp:/tmp'
    }
}

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
}