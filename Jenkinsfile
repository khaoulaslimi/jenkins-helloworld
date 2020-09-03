node {
   stage('clone') {
       git 'https://github.com/khaoulaslimi/jenkins-helloworld.git'

   }
   stage('build') {
    sh script:'javac Main.java'
}
stage('run') {
 sh script: 'java Main'
}
}

