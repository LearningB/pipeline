pipeline{
    agent any
        stages{
        stage("1"){
            steps{
                withMaven{
                    sh "mvn clean verify"
                }
                echo "Testing 123 but for what"
            }
        }
    }
}