node('built-in') 
{
    stage('Continuous Download_loan') 
	{
    git 'git clone https://github.com/ajcareercoach/maven.git'
	}
    stage('Continuous Build_loan') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
