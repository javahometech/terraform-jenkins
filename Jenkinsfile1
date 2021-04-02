pipeline{
  agent any
  stages{
    stage('terraform init'){
      steps{
        sh "terraform init"
      }
    }
  }
  }
def getTerraformPath(){
  def tfHome = tool name: 'terraform-12', type: 'org.jenkinsci.plugins.terraform.TerraformInstallation'
  return tfHome
}
