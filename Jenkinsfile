node {
    stage('clone') {
        git branch: 'main', url: 'https://github.com/MohamedAli-Bousleh/Hello-jenkins.git'

    }
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
