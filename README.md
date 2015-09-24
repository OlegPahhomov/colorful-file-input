# colorful-file-input


Check out here.
http://s22.postimg.org/l3oxd6zwx/colorful_file_input.png

Pure css solution (with jQuery filling text inputs).

It has some extra css, but I'm sure you can figure it out.
I tested it in Chrome, Firefox, IE. For IE file input works too, but you need to modify flexbox, because it wasn't working.


Idea.
###### 1. Take file input. Surround with div and make input fill div and be clickable.
###### 2. Make it transparent.
###### 3. Move it to the front or move background to the back.
###### 4. Make background (f.e a button) and make it fill the same area.
###### 5. Add disabled input text to the right to display uploaded files, make it show "2 files" when 2 files are added. (There is commented version of comma separated values)
###### 6. Edit css to make stuff nice
###### 7. Add hover effect to the "Choose Files" button. On hover of our invisible "top" element we need to modify underlying element.

P.S jQuery could be easily replaced w js.


I am using BEM CSS, great stuff:
http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/