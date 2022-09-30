node
{
    stage('Checkout'){
        
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Amitbaviskar/Webapp_project.git']]])
    }
    stage('Build') {
        echo "Build the code"
        }
    stage('unit testing'){
        echo "Unit testing"
        }
    stage('Delivery'){
        echo "delivery the code"
        }
}
