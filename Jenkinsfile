node {

   def registryProjet='landreau/'
   
     stage('Info') {
         sh 'docker version'
         sh 'docker info'
    }

    stage('Clone') {
          checkout scm
          sh 'git clone https://github.com/Jffr-Lndr/app-php.git'
    }

    stage('Build') {
      sh 'docker-compose up -d'
    }

}
