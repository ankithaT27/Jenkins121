pipeline{
   agent any
   stages{
     stage("build"){
         steps{
           echo "Build step"
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

