## BitMap2SVG



🔥Original project address: https://github.com/tfx2001/python-turtle-draw-svg ；

🔥You can convert the bitmap to svg and then use the turtle library to draw it, and save it as an **.eps** file ;



## Demo

### 🔥Input:

![](https://github.com/Inmessionant/BitMap2SVG/blob/main/2.jpg)



### 🔥Output:

![](https://github.com/Inmessionant/BitMap2SVG/blob/main/result.png)





## Usage



**Default command（Run main.py directly）**

```
python main.py  2.jpg
```

**Change input picture name**

```
python main.py  --filename cornell.png
```

**Parameter**

```
Convert an bitmap to SVG and use turtle libray to draw it.

positional arguments:
  filename              The file(*.jpg, *.png, *.bmp) name of the file you
                        want to convert.

optional arguments:
  -h, --help            show this help message and exit
  -c COLOR, --color COLOR
                        How many colors you want to draw.(If the number is too
                        large that the program may be very slow.)
```