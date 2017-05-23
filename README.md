# This is repository with my labs on asm.net

- ### loop
  **_CX_** - counter of cycle(dec CX->comparison CX with 0)
  ```
      mov bx, 0   ;initialize bx with 0
      mov cx, 5   ;number of cycles
  m1: inc bx      ;label
      loop m1     ;go to m1, if cx != 0
  ```
---
