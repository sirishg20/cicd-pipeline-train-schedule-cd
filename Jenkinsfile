pipeline {
    agent any 
	
    stages {
        stage('one') {
            steps {
                echo "Build was completed"
            }
        }
        stage('Two') {
            steps {
                echo "Second test was completed"
            }
        }
        stage('Three') {
            steps {
                echo "Info: $mvn version"
            }
        }
    }
}
