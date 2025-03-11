pipeline {
   agent any
   stages{
    stage('CodeScan'){
        steps{
            sh 'trivy fs . -o result.html'
            sh 'cat result.html'
        }
    }
    stage('dockerImageBuild'){
        steps{
            sh 'echo "docker -v'
        }
}
    stage('pushImage'){
        steps{
            sh 'docker ps'
        }
    }
   } 

}