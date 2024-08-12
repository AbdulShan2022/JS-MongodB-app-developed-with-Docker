// def gv

pipeline {
    agent any
    // parameters {
    //     choice(name: 'VERSION', choices: ['1.1.0', '1.2.0', '1.3.0'], description: '')
    //     booleanParam(name: 'executeTests', defaultValue: true, description: '')
    // }
    stages {
        stage("init") {
            steps {
                script {
                  echo 'Init the application ....'
                   // gv = load "script.groovy" 
                }
            }
        }
        stage("build") {
            steps {
                script {
                  echo 'Building the application ....'
                  echo 'Application built'
                    // gv.buildApp()
                }
            }
        }
        stage("test") {
            // when {
            //     expression {
            //         params.executeTests
            //     }
            // }
            steps {
                script {
                  echo 'Testing the application ....'
                    // gv.testApp()
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                  echo 'Deploying the application ....'
                    // gv.deployApp()
                }
            }
        }
    }   
}
