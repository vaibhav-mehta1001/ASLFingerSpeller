# ASLFingerSpeller
This program detetcts ASL Alphabet in real time, using a CNN. 
The training data was binarised, and all inputs are binarised as well. This allowed the Cov Net to "focus" on patterns and features 
that truly mattered, as opposed to irrelant details about skin colour, background, etc. 
This improved the overall accuracy, in fewer training steps, however, sybmols the accuracy between signs that are similar looking went down. 
Individual frames are taken from video and then classifies by the graph. 
