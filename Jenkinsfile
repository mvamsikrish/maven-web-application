node{
    def mavenhome = tool name : "Maven3.8.3"
    stage('CheckOutCode')
    {
        git branch: 'development', url: 'https://github.com/mvamsikrish/maven-web-application.git'
    }
    stage('Build')
    {
        sh "${mavenhome}/bin/mvn clean package"
    }
   /* stage('emailnotification')
    {
    mail bcc: '', body: 'email', cc: '', from: '', replyTo: '', subject: 'emialemail', to: 'm.vamsikrish1@gmail.com'
    }*/
}
