pipeline {
	agent any
	
	stages 
	stage ('Run ATC checks') {
			steps {
				abapCi abapPackagename: 'ZRAP400_0011', runAtcChecks: true, sapSystemLabel: 'TRL'
			}
		}
	}
	
}		
			
