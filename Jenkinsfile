pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Build starting'
            }
        }

        stage('Run Tests'){
        steps {
	echo 'Starting DAI Runner...'
            bat 'DAIrunner.exe -v testcase http://eval50.dai.eggplant.cloud/ wojciech.kuzniarz@keysight.com PapaSmerf LOGIN  wojciech.kuzniarz@eggplantsoftware.com WKLocal WK_CICD.suite'
        }
    }
    
}
}
