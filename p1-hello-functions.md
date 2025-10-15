<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius: 12px;">
<video controls style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 12px;">
<source src="./video/p1-around-the-border-preview.mp4" type="video/mp4">
Around the Border Challenge
</video>
</div>
<br /><br />

[🏠 Home](./README.md)

# Project 2: Hello Functions

## Tutorial

1. Go to: https://makecode.microbit.org/
2. Select **New Project** and name it `Around the Border` and click **Create**.

   <img src="./images/microbi-makecode-name-project.png" style="border: solid 1px grey" />

3. In the previous lesson we made a dot move back and forth. Then we had it move around the the edges in a loop.

4. For this tutorial we will clean up the blocks by using **Functions**

5. Think of **Functions** as blocks that let us re-use a set of instructions.

6. In the workspace `remove/delete` the **on start** block.

7. In your **toolbox** click on: `Advance > Functions`

8. Select **Make a Function** and name it `TopLeftToRight`

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius: 12px;">
<video controls style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 12px;">
<source src="./video/p1-hello-functions-create-function-block.mp4" type="video/mp4">
Create Function: TopLeftToRight
</video>
</div>
<br /><br />

9. Add **show leds** to the function block **TopLeftToRight** and highlight the first top-left square.

10. Then repeat this three more times. Selecting the 2nd block, 3rd block, and 4th block.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius: 12px;">
<video controls style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 12px;">
<source src="./video/p1-hello-functions-add-blocks-to-function-block.mp4" type="video/mp4">
Add blocks to function block
</video>
</div>
<br /><br />

11. Under the **Toolbox > Functions** click and drag the **call TopLeftToRight** into the **forever** block.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius: 12px;">
<video controls style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 12px;">
<source src="./video/p1-hello-functions-add-function-block-to-forever-block.mp4" type="video/mp4">
Add function block to forever block
</video>
</div>
<br /><br />

12. Using the same process create functions for: **TopRightToBottom, BottomRightToLeft,** and **BottomLeftToTop**

13. Then add the **show leds** for each box,.. just as the name describes it.

14. Add each new function to the **forever** block.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius: 12px;">
<video controls style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 12px;">
<source src="./video/p1-hello-functions-complete.mp4" type="video/mp4">
Functions added to Forever Loop with Final Process
</video>
</div>
<br /><br />

> Completed

<hr />

## Challenge: Pacing Giraffe

Use two functions: `WalkLeft` and `WalkRight` to make a Giraff walk back forth. Remember to place the functions in the `forever` block

![hint]

> Add the Basic > show icon block and change it to the giraff as reference. Just add it to the workspace

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius: 12px;">
<video controls style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 12px;">
<source src="./video/p1-hello-functions-pacing-giraffe.mp4" type="video/mp4">
Pacing Giraffe Microbit
</video>
</div>
<br /><br />
