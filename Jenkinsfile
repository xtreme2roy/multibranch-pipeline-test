node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Get some code from a GitHub repository
   git url: 'https://github.com/xtreme2roy/multibranch-pipeline-test.git'
   sleep(30)

   // Mark the code build 'stage'....
   stage 'Build'
   println 1
   sleep(30)
   
   // deploy stage
   stage 'Deploy'
   println 2
   sleep(30)
   
   //test stage
   stage 'Test'
   println 3
}
