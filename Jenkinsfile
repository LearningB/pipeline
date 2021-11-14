pipeline{
    agent any
        stages{
        stage("1"){
            steps{
                withMaven(
                    maven:'maven',
                    globalMavenSettingsConfig: "MyGlobalSettings"
                ){
                    mvn clean
                }
                echo "Testing 123 but for what"
            }
        }
    }
}