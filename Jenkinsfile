pipeline{
  agent{
    node{
      label 'docker-agent-alpine'    
    }
  }
  stages{
    stage('Build'){
      steps{
        echo "Building.."
        sh '''
        echo "Also building.."
        '''
      }
    }
    stage('Test'){
      steps{
        echo "Testing.."
        sh '''
        echo "Also testing.."
        '''
      }
    }
    stage('Deliver'){
      steps{
        echo "Delivering.."
        sh '''
        echo "Also delivering.."
        '''
      }    
    }      
  }
}
