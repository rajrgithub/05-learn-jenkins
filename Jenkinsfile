/*
pipeline {
    agent {
        label 'ansible'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    post{
       always{}
            echo 'send email'
       }
    }
}
*/

/*
@Library('roboshop') _

ci()
ci.call()

*/


@Library('roboshop')_

pipeline{
    agent any
    stages{
        stage('Test Groovy'){
            steps{
                script{
                print '****** pipeline script'
                def abc= "hello"
                def xyz= 10

                print "abc= ${abc}"
                print "xyz=${xyz}"

                print abc
                }
            }
        }
    }
}

*/

@Library('roboshop')_

pipeline{
    agent any
    stages{
        stage('Test Groovy'){
            steps{
                script{
                   test.testgroovyfun()
                   test()
                }
            }
        }
    }
}