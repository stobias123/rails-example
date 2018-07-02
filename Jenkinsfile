/* Assign our work to an agent labelled 'docker' */
node() {
    checkout scm
    stage 'Install Gems'
    sh 'bundle install'
    stage 'Prepare Database'
    sh 'rake db:migrate'
    stage 'Security scan'
    stage 'Deploy to QA'
    sh 'echo hello'
    stage 'Deploy to QA'
    sh 'echo prod'
}
