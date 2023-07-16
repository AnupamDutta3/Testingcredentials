pipeline { 
agent {
        label 'slave-2'
    }
    environment {
        TEST = credentials('Test-1-credential')
         }
    stages {
        stage ('This is the id, username, and password') {
        steps {
            echo "${TEST}"
            echo '{TEST_USR}'
            echo '${TEST_PSW}'
        }
    }
    }
}
