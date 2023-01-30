node('master')
{
    stage('Continuous Download Products')
        {
    git 'https://github.com/UjjalKrRoy/devops1.git'
        }
    stage('Continuous Build Products')
        {
    sh label: '', script: 'mvn package'
        }
}






















