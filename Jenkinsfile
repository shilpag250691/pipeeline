pipeline {
         agent any
         stages {
                 stage('Git Step') {
                 steps {
                     echo 'This is my GitStep'
		     git --version
                 }
                 }
                 stage('Maven') {
                 steps {
                    echo 'This is my MavenStep'
		    mvn --version
                 }
                 }
                 stage('Transfer of jar to server') {
                 steps {
                       touch a.jar
		                   cp a.jar/tmp
                 }
                 }
                 
              }
}
