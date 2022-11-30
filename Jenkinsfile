node('master') 
{
    stage('Continuous Download products') 
	{
    git 'https://github.com/dscmaruf/devops1-master.git'
	}
    stage('Continuous Build products') 
	{
    sh label: '', script: 'mvn package'
	}
}
