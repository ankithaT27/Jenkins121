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

post{

   failure{
      echo "failure"
}

   success{
      echo "success"
   }
   }

