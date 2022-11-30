node('master') 
{
    stage('Continuous Download master') 
	{
    git 'https://github.com/dscmaruf/devops1-master.git'
	}
    stage('Continuous Build master') 
	{
    sh label: '', script: 'mvn package'
	}
}
