## Awesome CSS Tips NoBody tells you!

In my day-to-day life, I hear a lot of people say that CSS is very difficult and they hate CSS. But no CSS is great and very easy to learn. Here are 8 tips to help you improve your CSS code

### 1.  inset property

Inset property in CSS is the shorthand for the four properties top, right, bottom, and left.


```
/* normal way 💩*/
.tip-1{
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
}
/* using inset property 🔥*/
.tip-1{
    position: absolute;
    inset: 0;
}
``` 
You can also use multiple values in inset property like this 👇

```
.tip-1{
/* When using 4 values it should be in this order */   
inset : 10px 20px 50px 30px; /* top👆 right👉 bottom👇  left👈 */
/* If you are using 3 values it looks like this */
inset: 5px 15px 10px; /* top👆  left👈/right👉 bottom👇 */
/* If there are 2 values, they are as follows */
inset: 4px 8px; /* top👆/bottom👇 left👈/right👉 */
}
``` 
If you want to know more about CSS inset property you can refer to this  [Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/inset).
And  [here](https://codepen.io/seyedi/pen/PoZQQVv) is a great pen about how the inset property works.

### 2. Clamp Function

Clamp function is another shorthand in CSS. You can use this instead of the min value, max value, and regular value. Here is the syntax of it.


```
.tip-2{
    width: clamp(100px, 40vw, 650px);
/*Here the regular value of width is 40vw but it does not go under 100px
 or over the 650px*/
}

It's just like this
.tip-2{
    width: 40vw;
    min-width: 100px;
    max-width: 650px;
}
``` 
The clamp function can be essential for you in responsive web design.
If you want to find more about clamp in CSS.  [This](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) is for you.

### 3. Disable selection

The next tip is how to disable selection in CSS.
It's simple as ABC. You just have to add this line to the code.

```
.tip-3{
    user-selection:none;
}
``` 

### 4. Validate number input 

I guess most of you didn't know about this.

When you are using number inputs you can use these pseudo-classes for validating the range of numbers can input. Here's how to do it👇
![Twitter post - 1 (1).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1640171326082/sMYdpIPGj.png)

### 5. break-word
Sometimes when you create a web page, long text overflows its content box, right?
Here is the solution for it👇
You can use "word-wrap" property with "break-word" to fix it.
![Twitter post - 1.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1640172162148/GoLNTpEFy.png)

### 6. Write Vertically in CSS
Writing vertically on a web page is a great way to get user attraction.
Here is how to do it.

![Twitter post - 2.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1640172258160/mdly9Iq1_.png)
Wanna know more about this property? Refer to these docs. 
1.  [writing-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/writing-mode)
2. [text-orientation](https://developer.mozilla.org/en-US/docs/Web/CSS/text-orientation)

### 7. Smooth Color Change on Hover

This is the last piece of tip today.
When you use the hover effect you can use this line of code for smooth transitions.

```
.tip-7{
    /* your code */
    transition: all .5 linear;
}
.tip-7:hover{
    /* your code */ 
}
``` 
After it looks like this.

![Twitter post - 2.gif](https://cdn.hashnode.com/res/hashnode/image/upload/v1640172917199/tzDBmwj93.gif)

That's all for today. If you enjoy reading this and find something useful like and share this. 
Do you suggest any improvements? Comment on it below.

Don't forget to follow me on  [Twitter](https://twitter.com/Lakira_md) 😉

Thanks for reading🙌!Happy Hacking🎉





