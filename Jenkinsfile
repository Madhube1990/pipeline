pipeline {
          agent any
          stages {
		stage(‘build’) {
		
                steps {
 			sh '''
				echo "this is build stage"
				sleep 2
			'''
                }
                }
		
		
		stage(‘deploy1’) {
		
                steps {
 			sh '''
				echo "this is deploy1 stage"
			'''
                }
                }

		stage(‘deploy2’) {
		
                steps {
 			sh '''
				echo "this is deploy2 stage"
			'''
                }
                }
		
       stage (‘Test’) {
	
       steps {
              sh '''
				echo "this is teststage"
			'''
       }
       }
    }
}
