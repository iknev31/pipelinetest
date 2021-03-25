pipeline {

    agent any

    stages {

        stage('clonethecode') {

            steps {

                // Get some code from a GitHub repository

                git 'https://github.com/iknev31/DevOpsTraining.git



                // Run Maven on a Unix agent.

                sh "javac hello.java"

                sh "java HelloWorld"



                // To run Maven on a Windows agent, use

                // bat "mvn -Dmaven.test.failure.ignore=true clean package"

            }

        }

	stage('test'){
		steps {
			sh "echo 'test stage'"

    }

}


