pipeline{
    agent any
        stages{
        stage("1"){
            steps{
                withMaven(
                    maven:'maven',
                    globalMavenSettingsConfig: "MySettings",
                    mavenSettingsConfig: 'settings.xml'
                ){
                    mvn clean
                }
                echo "Testing 123 but for what"
            }
        }
    }
}