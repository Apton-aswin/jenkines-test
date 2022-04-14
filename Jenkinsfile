pipeline{
agent any
stages 
{
stage('Build') 
{
steps{
    git credentialsId: 'github-token-key', url: 'https://github.com/aswin-apton/jenkines-test.git'
    bat 'python hello.py'
echo "Building the Code.........."
}
}
}
}
