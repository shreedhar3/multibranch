node('master') 
{
    stage('Continuous Download') 
	{
    git https://github.com/shreedhar3/multibranch.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
