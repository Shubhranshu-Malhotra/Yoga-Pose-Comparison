# Yoga Asan Comparison
A program that supervises the Yoga asan a user is doing and checks if it is being done correctly by employing pose estimation using `tf_pose` and pose comparison using `dynamic time wrapping`.   
  

This project employs pose estimation and pose similarity comparison in order to detect if the asan being done in 2 given videos given asan video and a reference video) is same or not.   
We also check the asan being done for correctness. By comparing a given video to the reference video we calculate a similarity score. A threshold can then be set and if value of similarity drops below that threshold, the user can be told that there is a problem in his movement during the asan.
