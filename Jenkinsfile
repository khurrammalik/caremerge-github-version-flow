node {
   stage "Checkout"
     echo "checkout"
     
   stage "Build"
     parallel 'build1':{
       echo "build1"
     }, 'build2':{
       echo "build2"
     }, 'build3':{
       echo "build3"
     }
    
    stage "Test"
      echo "Test"
}
