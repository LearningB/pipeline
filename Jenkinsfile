pipeline{
    agent any
        stages{
        stage("1"){
            steps{
                withMaven(
                    maven:'maven',
                    globalMavenSettingsConfig: "MySettings",
                    mavenSettingsConfig: 'MySettings'
                ){
                    mvn clean -s settings.xml
                }
                echo "Testing 123 but for what"
            }
        }
    }
}