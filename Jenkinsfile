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
            bat 'DAIrunner.exe -v testcase http://10.211.55.4:8000/ wojciech.kuzniarz@keysight.com PapaSmerf LOGIN  wojciech.kuzniarz@eggplantsoftware.com WKLocal Studio.suite'
        }
    }
    
}
}
