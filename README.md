Using
=====

Clone this into your QMK installation, inside the redox dir.


```bash
cd ~/qmk_firmware/keyboards/redox/keymaps
git clone git@github.com/elmarcoh/redox-ark.git
```

Then you can compile with

```
qmk compile -kb redox/rev1 -km ark
```

and then flash with

```
qmk flash -kb redox/rev1 -km ark
```


Then reset the keyboard; the reset combo is the first little key on the thumb cluster + `q`
