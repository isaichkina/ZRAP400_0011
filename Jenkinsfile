pipeline {
	agent any
	
	stages {
		stage ('Run Unit tests') {
			steps {
				abapCi abapPackagename: 'ZRAP400_TRAVEL_0011', runUnitTests: true
			}
		}
	stage ('Run ATC check') {
			steps {
				abapCi abapPackagename: 'ZRAP400_TRAVEL_0011', runUnitTests: true
			}
		}
	}
	
}		
			
