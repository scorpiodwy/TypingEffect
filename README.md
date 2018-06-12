# TypingEffect

index.html is the main. To run it, just open it with any browser, or drag it into a browser.

First version: typing phone number and password effect.
In images folder, I prepare two subfolders of images, which were splited from two gif.
There are a lot online gif splitter to use. You can use any of them to split your gif to images.

About the effect:
When user types phone number in the first input field, the Chi Cat also types.
When user types password in the second input field, the Chi Cat turns his head.

About code:
Phone number input is with three methods, onkeypress, onkeydown, and onfocus.
onkeypress directly returns a JS code block to accept numbers as input only.
onkeydown and onfocus call two JS functions.
enter_effect(event) is the JS function to let Chi Cat types with user typing.

Password input is the two methods, onkeydown and onfocus.
psw_effect(event) function is similar to enter_effect(event), but it can accept all inputs (enter_effect only accept numbers).
In these two methods, I loop the images if the inputing stream is over the size of images. Meanwhile, the Chi Cat stops if the input field is empty even user click 'delete'


