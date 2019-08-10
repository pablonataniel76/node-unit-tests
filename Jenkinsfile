pipeline {
    
    agent none;
    
    enviorement {
        myUsername = "PabloNataniel"
    }
    
    stages {
        stage ("Build") {
            steps {
                script {
                    node {
                        println "Mi primer pipeline en git"
                    }
                }
            }    
        }
        
        stage ("Test") {
            steps {
                script {
                    node {
                        println "Mi primer test"
                    }
                }
            }    
        }
        
        stage ("Develop") {
            steps {
                script {
                    node {
                        println "Mi primer develop"
                    }
                }
            }    
        }
    }
}
