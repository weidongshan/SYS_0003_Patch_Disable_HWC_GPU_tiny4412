  
Patch for andrid 5.0.2 to disable HWC&GPU, for weidongshan's android video tutorial.  
  
Usage:  
  
cd android-5.0.2  
    
patch -p1 < ../android-5.0.2_no_hwc_no_gpu.patch  
  
. setenv  
  
lunch full_tiny4412-eng    
  
make -j4  
  
./gen-img.sh  
   
     