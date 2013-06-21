progressbar.py
==============

- Simple python progress bar with timer
- Easy to add to existing code

How to use
----------

    # Make a ProgressBar instance with the length of task (number of iterations needed)
    prog = ProgressBar(100)
    
    # Start the main loop
    for i in some_object:
    
        # call the tap method to update the progress bar
        prog.tap()
        
        # rest of code here
  
  






