node {
     stage('----- 테스트 Clone repository -----') {
         checkout scm
     }

     stage('----- 테스트 Build image -----') {
         sh ' docker image build -t example/echo:latest .'
     }
}
