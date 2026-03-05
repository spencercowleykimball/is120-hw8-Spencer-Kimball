# is120-hw8-Spencer-Kimball

**Include in ReadMe**

1. Various screenshots of different stages of your animation throughout your development process:

Step 1:

![Step 1](step1.png)

Step 2:

![Step 2](step2.png)

Step 3:

![Step 3](step3.png)

Step 4:

![Step 4](step4.png)

Step 5:

![Step 5](step5.png)

Step 6:

![Step 6](step6.png)

Step 7:

![Step 7](step5.png)

2. Explain how you got certain stages of the animation completed and what it was like to break this problem down step by step.

At step 1 the rotating was definitely not correct, and I wasn't sure how to get the angled edges of the border.
At step 2 the rotating was still terrible.
At step 3 I wasn't sure how to get them all to be overlapping without adding a container div, and I wasn't sure if that would count as a div for the animation. 
At step 4 I decided that having a div container wouldn't count as a div to the animation div count since there were no animations happening to the container itself. I added position: flex to the container and position: absolute to the 3 div's for the animation to get them to overlap. The length of the borders were being weird at this point (as you can see from the gaps...but I genuinely don't know what I changed to make it change back to the regular lengths).
At step 5 and step 6 the background was not playing nice with the animation. I was trying to delay the middle fill since it looked like there was a slight delay in the video animation for the assignment for the inside fill. However, if I added a delay to the animation then the fill would fill in but then dissapear, and the background was showing up at the beginning due to the delay before the animation started.

3. Describe when something didn't work as expected. Maybe something you had to change or learned because of it

I looked up why this was happening, and this because I didn't have the animation-fill-mode: forwards; inside of the fill div. This allowed the background to fill in and stay correctly.

You can't tell from the pictures, but the rotating pieces still didn't have the angled edges of the border. After watching a youtube video about coloring the borders I realized that I needed to have a transparent border for the other two pieces of the border in order to make the edges angled!

The timing still may not be exactly perfect, but at this point I think it is pretty dang close!

4. Publish using GitHub pages and include the live URL in your repo about section. Submit the GitHub repo URL in LearningSuite.




**HW Instructions**

Copy the following CSS Animation.

You can use whatever resources you want (look up documentation, describe the problem to ChatGPT, etc.). I only ask that you don't paste the video itself directly into AI to see how it was done. To be honest, it probably won't be very good at telling you that either.

- You should only use 3 divs for the animation
- The animation should not loop, just trigger on load and stay on the end frame after animating
- You will want to use the transform property, I would look up documentation on this
- In your README.md include the following:
