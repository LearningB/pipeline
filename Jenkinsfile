pipeline{
    agent any
        stages{
        stage("1"){
            steps{
                withmaven(maven:'apache-maven-3.6.3'){
                    maven clean
                }
                echo "Testing 123 but for what"
            }
        }
    }
}