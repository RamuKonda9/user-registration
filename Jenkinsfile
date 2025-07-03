
pipeline {
       agent any
        environment {
             PATH - '/opt/maven/bin : $PATH'    //Adds maven's path to system path variable
                           }
            stages {
	stage('build') {
                         steps {
                            sh 'mvn clean install'   //runs maven clean install to build prj
                                }
                        }
	}
        }
