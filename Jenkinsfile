pipeline{
  agent any
  stages{
    stage(checkout)
    {
      steps{
        sh """
              javac Java1.java
              java Java1
           """
      }
    }
    stage(build)
    {
      steps{
        echo "world"
      }
    }
    stage(test)
    {
      steps{
        echo "varsha"
      }
    }
    stage(deploy)
    {
      steps{
        echo "Blue"
      }
    }
  }
}

    
