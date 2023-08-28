# gpnn-road-todo

[x] visualize correlation matrix 

[ ] it seems that earlier bhwc was going in as input to pyrdown. i'm pretty sure it requires bchw. i have made the change, can you confirm that my assumption is correct? 

  - i think there shouldnt be any permute's in pyrdown

  - find all the places in gpnn where resize_bhwc is being used. confirm that the last column is 5 or 3 ( i.e. channels)

<details>
  <summary> gpnn </summary>
  
  ```DBG_GPNN=1 DBG_HIGH_PERCENT=1 DBG_ROAD_EVAL_LOOP_BREAK=1 python run_multi.py --purge true --retrains false```
  
  [ ] __how are keys made?__
  
  
  
  [X] remove dutils from cifar, and use the github version
  
  [ ] how many levels and when to stop?
  
  [X] pyrdown argument list
  
  [ ] above image size?

  [ ] visualize some filled images at high percentage size. early break in eval loop

  [ ] is holefilling problematic at any percentage? ( high area i think )

  [ ] use nearness?
  
  ---
</details>

[ ] code for detection of imputed areas
