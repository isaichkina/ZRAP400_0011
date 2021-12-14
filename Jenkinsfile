pipeline {
	agent any
	
	stages {
		stage ('Run Unit tests') {
			steps {
				abapCi abapPackagename: 'ZRAP400_0011',  runUnitTests: true, sapSystemLabel: 'TRL'
			}
		}
	stage ('Run ATC check') {
			steps {
				abapCi abapPackagename: 'ZRAP400_0011', runUnitTests: true, runAtcChecks: true, sapSystemLabel: 'TRL'
			}
		}
	}
	
}		
			
