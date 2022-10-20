pipeline {
    agent any 
        stages {
            stage('Cloning from Git hub'){
                steps{
 
checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/RAKHEE001/maven-web-application.git']]])
                }
            }
        
        stage('build the code pipeline'){
            steps{
                echo"Build the code Pipeline"
            }
        }
        
        stage('test the code built'){
        steps{
            echo"test the code built"
        }
        }
        
        stage('Deploy the Tested code'){
            steps{
                echo"Deploy the tested code"
            
            }
        }
        
        stage('Release the code into the Production server'){
            steps{
                echo"release the code in Production servers"
            }
        }
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        }  
        
    
}
