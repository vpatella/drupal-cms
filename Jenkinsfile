node {
	stage 'Checkout'
		checkout scm

	stage 'Clean'
		sh 'mvn clean'

	stage 'Build'
		sh 'mvn install'

}
