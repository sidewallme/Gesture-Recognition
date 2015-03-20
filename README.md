# Gesture-Recognition

Step 1  
Receive signal to start processing  

Step 2
Start update min/max

Step 3  
while (head.y - min_height >= threshold){  
  <p>send msg(min_height);</p>  
}  
send signal(REACH_MIN) //squating is over
GOTO step 4  

Step 4  
while ( max_height - max(head,leftHand,rightHand) >= threshold){  
  <p>send msg(max_height);</p>  
}  
send signal(REACH_MAX) //jumping is over

Step 5
Receive signal to end processing  
