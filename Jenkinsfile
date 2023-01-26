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

/*
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
*/

/*
@Library('roboshop')_

pipeline{
    agent any
    stages{
        stage('Test Groovy'){
            steps{
                script{
                    print '****** pipeline script'
                    abc= "hello"
                    def xyz= 10

                    print "abc= ${abc}"
                    print "xyz=${xyz}"

                    print abc
                }
                script{
                  print "abc= ${abc}"
                }
            }
        }
        stage('Test var access'){
            steps{
                script{
                    print "abc= ${abc}"
                }
            }
        }
    }
}
*/

/*
@Library('roboshop')_
pipeline{
    agent any
    stages{
        stage('Test Groovy'){
            steps{
                script{
                    print '****** pipeline script'
                    env.abc= "hello"
                    def xyz= 10

                    print "abc= ${abc}"
                    print "xyz=${xyz}"

                    print abc
                }
                script{
                  print "abc= ${abc}"
                }
            }
        }
        stage('Test var access'){
            steps{
                script{
                    print "abc= ${abc}"
                }
            }
        }
    }
}
*/

@Library('roboshop') _

env.abc = "Some Data"
test1.new1()