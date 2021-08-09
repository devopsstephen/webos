pipeline{
     agent any
     stages{

             stage('git checkout'){
                   steps{

                       git 'https://github.com/kliakos/sparkjava-war-example.git'
          		   }
	         }


	   stage('mavenpackage'){

               steps{

                      echo "mvn package"
	       }

                   }

		   stage('deploy'){

                        steps{

                           echo "deploy"
			}
		   }
     } 
    
 
}
