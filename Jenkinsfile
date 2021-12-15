pipeline {
	agent any
	
	stages {
		stage ('Run Unit tests') {
			steps {
				abapCi abapPackagename: 'ZRAP400_0011',  runUnitTests: true, sapSystemLabel: 'TRL'
			}
		}
	
	
}		
			
