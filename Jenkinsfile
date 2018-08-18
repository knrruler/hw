node {
    
    stage ('SCM Cehckout'){
        
        git credentialsId: 'Git_hub', url: 'https://github.com/knrruler/hw.git'
    }
    stage ('Maven Package'){
        
            'package'
             echo 'Testing the maven package block'
    }
    stage ('Email Notification')
    
    {
        mail bcc: '', body: '''Hello..!
this is jenkins testing mail.''', cc: '', from: '', replyTo: '', subject: 'jenkins_test_email', to: 'knrruler@gmail.com'
        
    }
        
}
