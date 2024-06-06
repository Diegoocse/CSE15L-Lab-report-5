Part 1:

For part one I created a simple java program that calculates the square of a number

1)The original post from a student with a screenshot showing a symptom and a description of a guess at the bug/some sense of what the failure-inducing input is. (Don't actually make the post! Just write the content that would go in such a post)

Title: Issue with Square Calculation

Hello tutors,

I'm trying to write a Java program that calculates the square of a number, but I'm getting unexpected results. Here's a screenshot of the output:

<imgwidth="399" alt="Screenshot 2024-06-05 at 11 13 18 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-5/assets/146890166/90e13e4e-3de3-4b0a-aa7b-de0302e974b2">

I think that this has to do with how I'm calculating the square. How can I fix this?


2)A response from a TA asking a leading question or suggesting a command to try (To be clear, you are mimicking a TA here.)

Hi,

So from what I can see from the output I do think that in fact its an issue with how you are calculating the square. The square of 8 is supposed to be 64 and not 0. I suggest you revise the logic on how you implement the calcualtion. Let me know if this helps!


3)Another screenshot/terminal output showing what information the student got from trying that, and a clear description of what the bug is.


It seems that I was able to fix the issue from you suggestion this is my new output which indeed shows that the square root of 8 as 64. The bug had to do with how I implemented the square calculation. Thanks!

<img width="572" alt="Screenshot 2024-06-05 at 11 42 10 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-5/assets/146890166/2449e52c-65da-4c05-9b54-1128ad4aca7b">

4)At the end, all the information needed about the setup including:

The file & directory structure needed

I only had one file for this lab report which was square.java 

The contents of each file before fixing the bug

<img width="517" alt="Screenshot 2024-06-05 at 11 05 20 PM" src="https://github.com/Diegoocse/CSE15L-Lab-report-5/assets/146890166/f42dc20b-925e-416a-bd34-2a158735271c">


The full command line (or lines) you ran to trigger the bug

`javac square.java`

`java square`


A description of what to edit to fix the bug

To fix the bug you have to edit the line int square = 0 * 0; to int square = number * number; in square.java. This is a logical error since we need to multiply the number to get the square not 0 * 0.


Part 2-Reflection:

There were many important things that I learned this quarter. One of the major ones that stuck out to me were vim and editing things from the command line. I think that this was one of my favorite topics this quarter. One thing that tutor Nikhil taught me was about rm -rf and that removes directories without any prompt for confirmation which is a command to use very carefully. These were some of the things I learned this second half of the quarter.
