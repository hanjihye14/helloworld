node {
     stage('----- Clone repository -----') {
         checkout scm
     }

     stage('----- Build image -----') {
         sh 'docker image build -t example/echo:latest .'
     }
      stage('----- Run image -----') {
         sh 'docker container run -d -p 9000:8080 example/echo:latest'
     }
     
      
}
