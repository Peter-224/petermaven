pipeline{
        tools{
        maven 'Maven394'
}
        agent{
                label 'Agent'
}
        stages{

        stage('fetch code'){
                steps{
                git 'https://github.com/Sonal0409/DevOpsClassCodes.git'

}
}
        stage('clean'){
                steps{
                        sh 'mvn clean'
}
}
        stage('compile'){
                steps{
                        sh 'mvn compile'
}
}

        stage('test'){
                steps{
                        sh 'mvn test'
}
}
        stage('package'){
                steps{
                        sh 'mvn package'
}
}
}
