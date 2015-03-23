Reviewer 1:
When I ran your code in a new project on my emulator, a red screen shows up and says that there is an application error on line 25. When I dismissed the error message, I was only able to see a solid blue window without any buttons. The window was blank. 

I suggest:
•	Delete line 1: (function(){
•	Delete line 8: 	});
•	Add:   allRows.push(theRow); At line 22
•	At line 68, Correct “assEventListener” to “addEventListener”
•	Add a semicolon at like 69 {showTeaVerdict(e.source.TeaColour);});
•	Line 60 Change “tesVerdict = null; to “teaVerdict = null;

•	Line 62 change “judgement” to “judgment”

Once making these changes, I was then able to see the “tea” portion of the assignment operating correctly. 
There was no navigation between windows, and there were not two separate windows in the code. The code submitted only had the “tea” portion of the assignment. I would suggest using buttons or tabs that we used in previous assignments to navigate between pages.
I was not able to see a “phone gadget” portion in the code of in the emulator. Use the code in the book for the various phone gadgets to all to a second window separate from the “tea” code. 
The problem would be that there was not any “phone gadget” code submitted in the code, and you would need to add this code to a win2. You could choose from the gadgets in the book such as a map, camera, compass etc. 

