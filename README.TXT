Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.




ANSWERS


21. Because there was no parameter to set a value therefore it is set to the default of 00:00.

23. You would need to call timeClick 60 times or call setTime and put hours to 1 and minutes to 0.

24. NumberDisplay digit = new NumberDisplay(10);

25. Rectangle window = new Rectangle(15 , 100);

26. The 2nd constructor to ClockDisplay lets you choose what hour and minute you want to set the clock to by utilizing the source code in the NumberDisplay class.

27. The 2 constructors have similarities because they both create 2 NumberDisplays for hours and minutes.
    The 2 constructors have differences because one does not allow you to set a time and the other does, also the one without the option to set the time has to use updateDisplay to set the time to a default of 00:00

28. p1.print("File3", true);
    p1.getStatus(3)

29. Square
    Triangle
    Circle

30. roof.changeSize(60, 180);
    roof.moveHorizontal(20);
    roof.moveVertical(-60);
    roof.makeVisible();

31. Yes, drawn = true;

32. 2

33.  Only the first negative number affects the result.

34. -4, -3, -2, -1, 0, 1, 2, 3, 4.

35. every number is a possible result except for m = 0.

