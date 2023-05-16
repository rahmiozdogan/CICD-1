node{
stage('SCM Checkout'){
def mvnHome = tool name:'maven-3', type: 'maven'
sh "${mvnHome}/bin/mvn package
}
"stage('Email Notification'){
mail bcc: '', body: '''hi welcome to jenkins
thanks
hari''', cc: 'rahmiozdogan1@gmail.com', from: '', replyTo: '', subject: 'jenkins job', to: 'haticesimsekehm@gmail.com'
}
}
