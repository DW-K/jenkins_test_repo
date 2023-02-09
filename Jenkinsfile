pipeline {
   agent any
   parameters {
      string(name: 'VERSION', defaultValue: '', description: 'deployment version')
      choice(name: 'VERSION', choices: ['1.1.0','1.2.0','1.3.0'], description: '')
      booleanParam(name: 'executeTests', defaultValue: true, description: '')
   }
   stages {
      stage("build") {
         steps {
            echo 'building the applicaiton...'
         }
      }
      stage("test") {
         steps {
            echo 'testing the applicaiton...'
         }
      }
      stage("deploy") {
         steps {
            echo 'deploying the applicaiton...'
         }
      }
   }
}
