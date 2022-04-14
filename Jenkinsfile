pipeline{
agent any
stages 
{
stage('checkout') 
{
steps{
    git credentialsId: 'github-token-key', url: 'https://github.com/aswin-apton/jenkines-test.git'
}
}
stage('build') 
{
steps{
    sh 'python hello.py'
}
}
stage('Compile') 
{
steps{
echo "Compiling the Project.........."
}
}
stage('Deploy') 
{
steps{
echo "Deploying the Project.........."
}
}
}
}
