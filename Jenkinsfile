node {

   def registryProjet='landreau/'

    stage('Clone') {
          checkout scm
    }

    stage('Build') {
            sh 'docker-compose run –rm compile'
    }
   
    stage('Push') {/*
       docker.withRegistry('https://index.docker.io/v1/' , 'hub_docker_id') {
              img.push 'latest'
              img.push()
          }/*/
       echo "test"
    }

}
