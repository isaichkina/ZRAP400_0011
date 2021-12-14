pipeline {
	agent any
	
	stages {
		stage ('Run Unit tests') {
			steps {
				abapCi abapPackagename: 'ZRAP400_0011',  runUnitTests: true
			}
		}
	stage ('Run ATC checks') {
			steps {
				abapCi abapPackagename: 'ZRAP400_0011', runAtcCheks: true 
			}
		}
	}
	
}		
			
