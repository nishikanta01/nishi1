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
                 sh "javac Demo.java"
                 sh "python3 main.py"
                 }
             }
         }
       }
   
