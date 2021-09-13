pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_BRANCH"
         }
      }
      stage('Verify Branch Again') {
         steps {
            echo "$GIT_BRANCH"
         }
      }
   }
}
