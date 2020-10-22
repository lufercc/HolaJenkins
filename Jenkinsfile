pipeline {
 agent any
 tools {
    gradle "gradle4"
 }
 stages {
    stage("build") {
         steps {
             bat 'gradle --version'
         }
    }
     stage("test") {
         steps {
             bat 'gradle uiTests'
         }
     }
     stage("deploy") {
         steps {
             bat "deploy application"
         }
     }
 }
}
