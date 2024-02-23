pipeline{
   agent any
     stages
         {
         stage("GIT")
             {
             steps
                 {
                 git "https://github.com/nishikanta01/jenkin1.git"
                 }
             }
         stage("run")
             {
             steps
                 {
                 sh "java Demo.jave"
                 sh "python3 main.py"
                 }
             }
         }
       }
   
