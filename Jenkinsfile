pipeline {
    
    agent none;
    
    enviroment {
        myUsername = "PabloNataniel"
    }
    
    stages {
        stage ("Build") {
            steps {
                script {
                    node {
                        println "Mi primer pipeline en git"
                        echo "Nombre de usuario ${myUsername}"
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
