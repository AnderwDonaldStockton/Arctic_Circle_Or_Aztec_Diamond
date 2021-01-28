# Arctic_Circle_Or_Aztec_Diamond
Hello, This project attempts to create and display something called the Arctic Circle or Aztec Diamond.
The rules for the generation of this grid can be seen on the YouTube channel Mathologer. The video link are here:
https://youtu.be/Yy7Q8IWNfHM
to skip just to the rules start about here: https://youtu.be/Yy7Q8IWNfHM?t=1270

How to operate:
Change line 62 to other numbers, the default I chose was 300
Change line 63 to overwrite the excel file at the desired location.
Close the excel file if open
Run the code in Matlab and wait for it to finish
open the excel file and see the results by zooming out to 10%

improvements:
The only way I could display this is by outputing the code to an excel file and then formating that file so that a specific number corrosponds with a specific color. Please let me know if there is something that can increase the speed of the code. I would also like to display this only in MATLAB but I do not know how to create a dynamic grid on a gui. My initial guess is display the matrix in a gui and then place a colorful square on top of the grid. I want to resize the grid to match how many times the code is run. Each time the loop cycles the matrix gets bigger and I was hoping to make this a dynamic graph, but I am not sure how to do this.
