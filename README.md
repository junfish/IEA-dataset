# IEA-dataset
  Large scale images dataset with both aesthetic and emotional labels
  The download link contains h5py file final_aes_emo.h5  
  The final_aes_emo.h5 contains 3 keys: image, aes, emo  
  images: 22086 images  
  aes: 22086 2-demension labels of one-hot encoding.  
  [0, 1] represents the high aesthetic quality, otherwise, [1, 0] represents the low aesthetic quality.  
  emo: 22086 8-demension labels of one-hot encoding.  
  [1, 0, 0, 0, 0, 0, 0, 0] represents amusement  
  [0, 1, 0, 0, 0, 0, 0, 0] represents excitement  
  [0, 0, 1, 0, 0, 0, 0, 0] represents awe  
  [0, 0, 0, 1, 0, 0, 0, 0] represents contentment  
  [0, 0, 0, 0, 1, 0, 0, 0] represents disgust  
  [0, 0, 0, 0, 0, 1, 0, 0] represents anger  
  [0, 0, 0, 0, 0, 0, 1, 0] represents fear  
  [0, 0, 0, 0, 0, 0, 0, 1] represents sad  
