pipeline {
	agent any
	
	stages {
		stage ('Run Unit tests') {
			steps {
				abapCi abapPackagename: 'ZRAP400_0011',  runUnitTests: false, sapSystemLabel: 'TRL'
			}
		}
	stage ('Run ATC checks') {
			steps {
				abapCi abapPackagename: 'ZRAP400_0011', runAtcChecks: true, sapSystemLabel: 'TRL'
			}
		}
	}
	
}		
