pipeline { 
    stage('master-branch-stuff'){
  agent any
  when{
    branch 'master'
  }
  stage('feature-branch-stuff') {
    agent any
    when { branch 'zzz' }
    steps {
        echo 'run this stage - only if the branch name started with feature/'
    }
}
