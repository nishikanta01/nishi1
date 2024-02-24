pipeline{
   agent any
     stages
         {
         stage("GIT")
             {
             steps
                 {
                 git "https://github.com/nishikanta01/nishi1.git"
                 }
             }
         stage("run")
             {
             steps
                 {
                 sh "java Demo.java"
                 sh "python3 main.py"
                 }
             }
         }
       }
   
