peline {
    agent any
    
    stages {
 
        stage('parallel 1') {
           
            parallel {
                stage('step1') {
                   
                    steps {
                        echo "noir"
                    }
                }
                stage('step2') {
                    
                   
                    steps {
                        echo "blanc"
                    }
                }
                
             }
        }
        stage('parallel2 ') {
           
            parallel {
                stage('step3') {
                   
                    steps {
                        echo "bleu"
                    }
                }
                stage('step4') {
                    
                   
                    steps {
                        echo "rouge"
                    }
                }
                
                    }
                }               
            }
    }
