# zmk-config
Here is ZMK config file for my CRKBD layout.  You can find out more about ZMK firmware [here](https://zmkfirmware.dev/)

It uses layers to shrink they keyboard so that finger travel is a maximum of 1 unit from the home row.

```
DEFAULT_LAYER
-------------------------------------------------     -------------------------------------------------
|       |   Q   |   W   |   F   |   P   |   G   |     |   J   |   L   |   U   |   Y   |   ;   |       |
|       | CTRL  |  ALT  |  GUI  |       |       |     |       |       |  GUI  |  ALT  | CTRL  |       |
-------------------------------------------------     -------------------------------------------------
|       |   A   |   R   |   S   |   T   |   D   |     |   H   |   N   |   E   |   I   |   O   |       |
|       |       |       |       | Shift |       |     |       | Shift |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
|       |   Z   |   X   |   C   |   V   |   B   |     |   K   |   M   |   ,   |   .   |   '   |       |
|       |       |       |       |       |       |     |       |       |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
                        |  ESC  |  BSP  |  Tab  |     [   -   | Space | Enter |
                        | Number| Symbol| Shift |     |Arrange|  Nav  | Thumb |
                        -------------------------     -------------------------

NUMBER_LAYER
-------------------------------------------------     -------------------------------------------------
|       |       |       |       | Zoom  | Zoom  |     |   :   |   7   |   8   |   9   |   0   |       |
|       |       |       |       | Mic   | Video |     |       |       |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
|       |Select |  CUT  | COPY  | PASTE |       |     |   .   |   4   |   5   |   6   |   /   |       |
|       | All   |       |       |       |       |     |       |       |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
|       |       |       |       |       |       |     |   +   |   1   |   2   |   3   |   *   |       |
|       |       |       |       |       |       |     |       |       |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
                        |  NUM  | FUN   |       |     |   -   |       |       |
                        |       |       |       |     |       |       |       |
                        -------------------------     -------------------------

SYMBOL_LAYER
-------------------------------------------------     -------------------------------------------------
|       |   !   |   @   |   *   |   &   |   |   |     |   |   |   [   |   ^   |   ]   |   :   |       |
-------------------------------------------------     -------------------------------------------------
|       |   ~   |   <   |   %   |   >   |   £   |     |   ?   |   (   |   $   |   )   |   /   |       |
-------------------------------------------------     -------------------------------------------------
|       |   `   |      |       |   =   |   €   |     |   +   |   {   |   #   |   }   |   \   |       |
-------------------------------------------------     -------------------------------------------------
                        |  FUN  |  SYM  |       |     |       |       |       |
                        |       |       |       |     |       |       |       |
                        -------------------------     -------------------------

NAVIGATION_LAYER
-------------------------------------------------     -------------------------------------------------
|       |       |       |       |       |       |     |       | Home  |  Up   |  End  | Page  |       |
|       |       |       |       |       |       |     |       |       |       |       |  Up   |       |
-------------------------------------------------     -------------------------------------------------
|       |       |       |       |       |       |     |       | Left  | Down  | Right | Page  |       |
|       |       |       |       |       |       |     |       |       |       |       | Down  |       |
-------------------------------------------------     -------------------------------------------------
|       |       |       |Screen |       |       |     | Prev  | Prev  | Next  | Next  | Fwd   |       |
|       |       |       |Capture|       |       |     |History|  Tab  |Window |  Tab  |History|       |
-------------------------------------------------     -------------------------------------------------
                        |       |  Del  |       |     |       |  NAV  |       |
                        |       |       |       |     |       |       |       |
                        -------------------------     -------------------------

ARRANGE_LAYER - Magnet window manager shortcuts
-------------------------------------------------     -------------------------------------------------
|       | 1/6th | 2/6th | Full  | 5/6th | 6/6th |     |       | Top   | Top   | Top   |       |       |
|       |       |       | Screen|       |       |     |       | Left  | Half  | Right |       |       |
-------------------------------------------------     -------------------------------------------------
|       | L 1/3 | L 2/3 | C 1/3 | R 2/3 | R 1/3 |     | Prev  | Left  | Bottom| Right | Next  |       |
|       |       |       |       |       |       |     | Screen| Half  | Half  | Half  | Screen|       |
-------------------------------------------------     -------------------------------------------------
|       | L 5/6 | 3/6th | Centre| 4/6th | R 5/6 |     |       | Bottom|Restore| Bottom|       |       |
|       |       |       |       |       |       |     |       | Left  |       | Right |       |       |
-------------------------------------------------     -------------------------------------------------
                        |       |       |       |     | ARR   |       |       |
                        |       |       |       |     |       |       |       |
                        -------------------------     -------------------------

THUMB_LAYER
-------------------------------------------------     -------------------------------------------------
|       | BT    |       | BT    | BT    |       |     |       | Input |       |       | Txt + |       |
|       | Clear |       | Set0  | Next  |       |     |       | Lang  |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
|       |       |       |       |       |       |     |       | Caps  | Emoji |       | Txt - |       |
|       |       |       |       |       |       |     |       | Lock  |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
|       |       |       |       |       |       |     |       |       |       |       |       |       |
|       |       |       |       |       |       |     |       |       |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
                        |       |       |       |     |       |       | Thumb |
                        |       |       |       |     |       |       |       |
                        -------------------------     -------------------------

function_layer
-------------------------------------------------     -------------------------------------------------
|       |       |       |       |       |       |     |       |  F7   |  F8   |  F9   |  F12  |       |
|       |       |       |       |       |       |     |       |       |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
|       |       |       |       |       |       |     |       |  F4   |  F5   |  F6   |  F11  |       |
|       |       |       |       |       |       |     |       |       |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
|       |       |       |       |       |       |     |       |  F1   |  F2   |  F3   |  F10  |       |
|       |       |       |       |       |       |     |       |       |       |       |       |       |
-------------------------------------------------     -------------------------------------------------
                        | Func  | Func  |       |     |       |       |       |
                        |       |       |       |     |       |       |       |
                        -------------------------     -------------------------

```
