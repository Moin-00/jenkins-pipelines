pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'Building the application...'
                // Add your build commands here
                build job :"boolPipeline" , parameters: [[$class :"BooleanParameterValue" ,name :"myBoolean",value :true]]//for parameterised Job
            }
        }
    }
}