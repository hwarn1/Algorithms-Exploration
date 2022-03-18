# Algorithms-Exporation

I can solve a pyraminx, usually in **less** than a minute.  

**How I solve(centre face method):**  
1. Position the cube so that each centre piece of the same colour is on the same face. 
2. Turn all small corners to so that their colours match the centre piece on each face.
3. Pick a colour/face and rotate the entire cube so that it is facing the floor.
4. Find that colour (blue for example) elsewhere on the cube and turn the large top corner so that the colour attached to the blue is on the same face as centre pieces of the same colour. Rotate the entire cube so that face in positioned toward me.
5. Whichever side the blue is *not* on, turn that large corner up once (L' or R).
6. Turn the top large corner so that the blue is facing me.
7. Turn the same large corner as in step 5 down (L or R').
8. Repeat steps 4-7 until bottom face is entirely blue.
9. Once bottom face is entirely the same colour, choose a different colour and face it to the floor (ensuring all centre pieces are the same colour).
10. Repeat steps 4-9 until pyraminx is completely solved.  

--In the case that step 6 is not possible, performing R, U, R' will fix the problem.--

**My recent solve times:**  
After 25 solves on March 18th, 2022:  
ao5 = 36.05s  
ao12 = 37.47s  
ao25 = 35.38s  
