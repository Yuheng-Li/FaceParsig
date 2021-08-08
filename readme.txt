This code is copied from https://github.com/zllrunning/face-parsing.PyTorch

I made changes in their test.py function 

to get face parsing result please first download their ckpt from 
https://drive.google.com/file/d/154JgKpzCPW82qINcVieuPH3fZ2e0P812/view
and save it in ./res/cp

then prepare your data folder which only contains face images 
(it should be a single face image aligned as celeba-hq dataset, I have no idea what will happen in the other cases)

Then run test.py    

Note1: dspth means data_path in evaluate()
Note2: saved results will be 512*512 res  
