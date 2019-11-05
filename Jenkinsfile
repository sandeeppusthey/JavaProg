pipeline {
   agent any

   stages {
      stage('Clone') {
         steps {
            bat 'git clone https://github.com/sandeeppusthey/JavaProg'
            echo 'This is clone step';
         }
      }
      stage('Build') {
         steps {
            echo 'This is build step';
         }
      }
      stage('Test') {
         steps {
            echo 'This is test step';
         }
      }
   }
}
