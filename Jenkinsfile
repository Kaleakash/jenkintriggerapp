pipeline{
    agent any 
        
        stages{
            
            stage("Ths is external jenkin script file"){
                
                steps {
                    echo "Welcome to Jenkin externa file part of GitHub account"
                    sh "ls"
                }
            }

            stage("Compile the program"){
                
                steps {
                    sh "javac App.java"
                }
            }

            stage("Run the program"){
                
                steps {
                    sh "java App"
                }
            }
        }
    
}