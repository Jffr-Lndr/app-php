node {

   def registryProjet='landreau/'
   
     stage('Info') {
         sh 'docker version'
         sh 'docker info'
         sh 'docker compose version'
    }

    stage('Clone') {
          checkout scm
    }

    stage('Build') {
      sh 'docker-compose up'
    }

    stage('Push') {
      /* docker.withRegistry('https://index.docker.io/v1/' , 'hub_docker_id') {
              img.push 'latest'
              img.push()
          }*/
       echo "test"
    }

}
