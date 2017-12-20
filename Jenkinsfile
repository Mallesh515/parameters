pipeline {
    agent any
    parameters {
        string(name: 'PERSON' , defaultValue: 'Mr Jenkins' , description: 'Who should I say hello to?')   
        choice(name: 'GENDER', choices:'Mr\nMrs', description: 'select your gender')
        booleanParam(name: 'DEBUG_BUILD', defaultValue: true, description: '')
               }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
