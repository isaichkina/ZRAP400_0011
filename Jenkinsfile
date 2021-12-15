pipeline {
	agent any
	
	stages {
		stage ('Run Unit tests') {
			steps {
				abapCi sapPackagename: 'ZRAP400_0011',  runUnitTests: true, sapSystemLabel: 'TRL'
			}
		}
	
	
}
	
}
			
