SET "please input temperature" TO DISPLAY
RECIEVE temp FROM KEYBOARD
IF temp <18 degrees THEN
SEND "Cold, the perfect temperature is for sleep is 18-21 degrees." TO DISPLAY
ELSE
IF temp >21 degrees
SEND "Perfect" TO DISPLAY
ELSE
SEND "No!, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
END IF 
END IF
END IF
