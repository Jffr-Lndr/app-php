node {

   def registryProjet='landreau/'
   
     stage('Info') {
         sh 'docker version'
         sh 'docker info'
    }

    stage('Clone') {
          checkout scm
    }

    stage('Build') {
      sh 'docker-compose up -d'
    }

}
