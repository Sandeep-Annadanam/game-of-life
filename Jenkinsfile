node {
	stage('SCM') {
	git https://github.com/Sandeep-Annadanam/game-of-life.git
	}

	stage('build the packages') {
		sh 'mvn package'
	}
stage('archival') {
archive 'target/*.jar'
	}
      }
