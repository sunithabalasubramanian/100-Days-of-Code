### Statement
~~~
If you adopted the "Follow the Right Wall" algorithm, you will complete Level 10. 
What is the JavaScript code you got? 
How many blocks did you have left? 
Assign it to the variable remaining_blocks.
~~~
### Code
~~~
# Cut and paste the JavaScript code and assign it 
# to the variable below 

level_10_code = '''while (notDone()) {
  if (isPathRight()) {
    turnRight();
  }
  if (isPathForward()) {
    moveForward();
  } else {
    turnLeft();
  }
}'''
# Transfer the value from Level 10 "blocks remaining"
# to the variable below 

remaining_blocks = 4
print("JavaScript code for Level 10")
print(level_10_code)
print("Number of blocks remaining", remaining_blocks)
~~~
