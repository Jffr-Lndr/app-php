node {

   def registryProjet='landreau/'

    stage('Clone') {
          checkout scm
    }

    stage('Compose') {
            sh 'docker compose up'
    }
   
    stage('Push') {/*
       docker.withRegistry('https://index.docker.io/v1/' , 'hub_docker_id') {
              img.push 'latest'
              img.push()
          }/*/
       echo "test"
    }

}
