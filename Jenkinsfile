pipeline {    
agent any    
stages {        
stage('Hello') {            
steps {                echo 'Hello World'            }        
}        
stage('Java Version') {            
steps {               sh 'java -version'            }        
} 
stage('compile project') {            
steps {               sh 'mvn clean package'            }        
}    

stage('test project') {            
steps {               sh 'mvn test'            }        
}    
}
}