// SCRIPTED
// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('Integration Test') {
// 		echo "Test"
// 	}
// }

//DECLERATIVE PIPELINE
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration test"
			}
		}
	} post {
		always {
			echo 'Im Awesome'
		}
		success {
			echo 'Im Successful'
		}
		failure {
			echo 'I Failed'
		}
	}	
}