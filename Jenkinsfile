node()
{
    stage('Checkout')
    {
        checkout scm
    }
    stage('Build')
    {
        sh 'mvn clean package'
    }
    stage('Deploy')
    {
        sh 'kubectl apply -f deployment.yaml'
    }
}