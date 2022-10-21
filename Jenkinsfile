node {
    stage('clone') {
        git 'https://github.com/Salimoukali/jenkins_java.git'

}
    stage('build') {
        sh 'cd jenkins_java'
   sh 'javac Main.java'
}
    stage('run') {
        sh 'java Main'

}
}
