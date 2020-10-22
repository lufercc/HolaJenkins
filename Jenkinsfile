pipeline {
 agent any
 tools {
    gradle "tt"
 }
 stages {
    stage("configuration") {
         steps {
             bat 'gradle uiTests'
         }
    }
 }
}
