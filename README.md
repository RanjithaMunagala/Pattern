# Pattern
Geometricalpatterns
SimpleImage.

This file have code to do simple colour patterns.

The parameters required in various functions are
col_width - required width of the each column in pixel count.
rep - Number of times the colours need to repeat in the pattern
colour - a list of lists where each element of the list represents a colour in RGB value.
row_height - required height of each row
size - length of side and height of daimond in pixel count.

Size of the image and the colours of patern depends on the parameters passed.

All the functions use similar functions with small changes to create a different pattern.

The following is an example what the images will look like if 4 colours are used.

ver_line(col_width, rep, colour) returns an image with vertical colour stripes.
![image](https://user-images.githubusercontent.com/66545190/121366369-0d745e80-c957-11eb-8f84-b28d2cccb3ed.png)

hori_line(row_height, no_rows, colour) returns an image with horizontal stripes.
![image](https://user-images.githubusercontent.com/66545190/121366569-372d8580-c957-11eb-8481-f3da9343c252.png)

diag_line1(col_width, rep, colour) or diag_line2(col_width, rep, colour) returns an image with diagonal stripes.
![image](https://user-images.githubusercontent.com/66545190/121366805-66dc8d80-c957-11eb-9e23-1c46489d6c24.png)

ver_dai1(size, rep, colour) or ver_dai2(size, rep, colour) returns an image with vertical daimonds.
![image](https://user-images.githubusercontent.com/66545190/121367044-98555900-c957-11eb-95e4-a054e255069e.png)

zig_dai1(size, rep, colour) or zig_dai2(size, rep, colour) returns an image with zigzag colour daimonds.
![image](https://user-images.githubusercontent.com/66545190/121367154-b1f6a080-c957-11eb-976a-2974cd6f3f3a.png)





