Student Name: Yilin Luo
NetID: yluo21
TA: Joseph Traversy

Project Explanation:

For this project, I used a list fragment to handle list of buttons and their states of being pressed, a detail fragment to be called by list fragment (through main activity), and a main activity. 

I have 20 buttons, each trigger different sounds. When switching from portrait view to landscape, the detail panel will show the last pressed button while in portrait view, then keep updating while buttons are pressed in the current landscape view. You can choose longer sounds to test the un-interrupted playing- I recommend playing number 12 or plus- those sounds are longer. 

I have two styles, one for API 21 and lower, another or API 21+. This APP performs best while in API 28, in API 26, the toast message updates slower, but orientation transition is alright in all API versions.
