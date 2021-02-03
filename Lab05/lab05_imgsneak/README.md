## Lab05 - Challenge Exercise - Img Sneak

You are not expected to complete this exercise.

Setup a flask server `imgsneak.py` that serves a 1px x 1px transparent png at a path /email/img.png?code=ABCDEFG

Where ABCDEFG is a unique code that can be anything.

When this route is accessed (via GET method), the unique code ABCDEFG should be printed to terminal.

Demonstrate to your tutor how you can send yourself an email (via any email account on the CSE machine) with an image in the email and how when they open the email your running flask server prints out the code.

Note: (you'll have to send a raw email with the code:
```html
<img src="http://127.0.0.1/email/img.png?code=yourname" />
```