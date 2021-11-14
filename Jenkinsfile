pipeline{
    agent any
        stages{
        stage("1"){
            steps{
                withMaven(maven:'apache-maven-3.6.3'){
                    mvn clean
                }
                echo "Testing 123 but for what"
            }
        }
    }
}