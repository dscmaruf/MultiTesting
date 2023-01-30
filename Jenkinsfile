node('master')
{
    stage('Continuous Download Master')
        {
    git 'https://github.com/UjjalKrRoy/devops1.git'
        }
    stage('Continuous Build Master')
        {
    sh label: '', script: 'mvn package'
        }
}












