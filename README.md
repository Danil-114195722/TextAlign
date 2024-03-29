# TextAlign

### Last version: 1.0.4

### Short description:

This module allows you to align text relative to the center, right, left and both sides

### It contains:

1. ```right(text, width)``` - this function align the "text" to right side with given "width"
2. ```left(text, width)``` - this function align the "text" to left side with given "width"
3. ```center(text, width)``` - this function align the "text" to center with given "width"
4. ```justify(text, width)``` - this function align the "text" to both sides with given "width"

### How to use:

```python
from text_align import justify


my_long_text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum sagittis dolor mauris, at elementum ligula tempor eget. In quis rhoncus nunc, at aliquet orci. Fusce at dolor sit amet felis suscipit tristique. Nam a imperdiet tellus. Nulla eu vestibulum urna. Vivamus tincidunt suscipit enim, nec ultrices nisi volutpat ac. Maecenas sit amet lacinia arcu, non dictum justo. Donec sed quam vel risus faucibus euismod. Suspendisse rhoncus rhoncus felis at fermentum. Donec lorem magna, ultricies a nunc sit amet, blandit fringilla nunc. In vestibulum velit ac felis rhoncus pellentesque. Mauris at tellus enim. Aliquam eleifend tempus dapibus. Pellentesque commodo, nisi sit amet hendrerit fringilla, ante odio porta lacus, ut elementum justo nulla et dolor."
aligned_text = justify(my_long_text, 55)
print(aligned_text)
'''
Output:

Lorem  ipsum  dolor  sit  amet,  consectetur adipiscing
elit.  Vestibulum  sagittis  dolor mauris, at elementum
ligula  tempor  eget.  In quis rhoncus nunc, at aliquet
orci. Fusce at dolor sit amet felis suscipit tristique.
Nam  a  imperdiet  tellus.  Nulla  eu  vestibulum urna.
Vivamus  tincidunt  suscipit  enim,  nec  ultrices nisi
volutpat ac. Maecenas sit amet lacinia arcu, non dictum
justo.  Donec  sed  quam  vel  risus  faucibus euismod.
Suspendisse  rhoncus  rhoncus felis at fermentum. Donec
lorem   magna,  ultricies  a  nunc  sit  amet,  blandit
fringilla  nunc.  In  vestibulum velit ac felis rhoncus
pellentesque.  Mauris  at tellus enim. Aliquam eleifend
tempus  dapibus.  Pellentesque  commodo,  nisi sit amet
hendrerit   fringilla,   ante   odio  porta  lacus,  ut
elementum justo nulla et dolor.
'''
```

### Installation:

```shell
pip install text-align==1.0.4
```
