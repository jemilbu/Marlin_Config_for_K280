# Known Issues on the K280

1. Stepper Motors
    - Jacob Milburn, 5/13/2022
        - Current firmware that has been uploaded to the printer does not drive the stepper motors correctly. Possible solutions online were checking the wiring, verifying that the motor drivers are configured correctly, that the end stops are set correctly and that the steps/mm were correct. 
        - I was able to determine that it was not the wires, and I believe the steps/mm to be correct, but I am not positive. 
        - Possible solution: Look up how HE3D configured their stepper motors and copy that configuration. Post to the FB group to see if anyone else has had the same issue. 
2. BLTouch offset
    - Jacob Milburn, 5/13/2022
        - Due to the Stepper Motor issue, I could not set X, Y, and Z offsets for the BLTouch. These will need to be configured before Auto Bed Levelling can be accurate.
        - Solution: Determine X, Y, and Z offsets (see Google for how-to)
