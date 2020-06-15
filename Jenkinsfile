pipeline { 
   stage('master-branch-stuff'){
  agent any
  when{
    branch 'master'
  }
  steps {
    echo 'run this stage - ony if the branch = master branch'
  }
}
  }
  stage('feature-branch-stuff') {
    agent any
    when { branch 'zzz' }
    steps {
        echo 'run this stage - only if the branch name started with feature/'
    }
}
}
