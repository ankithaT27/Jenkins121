pipeline{
   agent any
   stages{
     stage("build"){
         steps{
           echo "Build step"
            git "https://github.com/ankithaT27/myfirstrepository.git"
            sh "httpd install"
         }
     }


      stage("test"){
         steps{
           echo "Test step"
         }
     }
   }
//adding post steps
   post{

   failure{
      echo " run if failure"
}

   success{
      echo " run if success"
   }
   }
}

