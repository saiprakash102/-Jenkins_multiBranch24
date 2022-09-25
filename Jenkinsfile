node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build') 
	{
    input 'waiting for tester approval'		
    sh label: '', script: 'mvn package'
	}
}
