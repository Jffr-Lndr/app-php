node {

   def registryProjet='landreau/'

    stage('Clone') {
          checkout scm
    }

    stage('Build') {
            sh 'docker compose up -d'
    }
   
    stage('Push') {/*
       docker.withRegistry('https://index.docker.io/v1/' , 'hub_docker_id') {
              img.push 'latest'
              img.push()
          }/*/
       echo "test"
    }

}
