

## Examples

![](https://github.com/x-hw/amazing-qr/blob/master/example/qrs0.jpg)

![](https://github.com/x-hw/amazing-qr/blob/master/example/qrs1.jpg)

![](https://github.com/x-hw/amazing-qr/blob/master/example/qrs2.jpg)

![](https://github.com/x-hw/amazing-qr/blob/master/example/c_qrcode.gif)![](https://github.com/x-hw/amazing-qr/blob/master/example/daftpunktocat-guy_qrcode.gif)

![](https://github.com/x-hw/amazing-qr/blob/master/example/zootopia_qrcode.gif)![](https://github.com/x-hw/amazing-qr/blob/master/example/daftpunktocat-guy_qrcode0.gif)

## Install

```python
# via pip
pip install amzqr
```

#### Common QR-Code

![](https://github.com/x-hw/amazing-qr/blob/master/example/0.png)

```python
amzqr https://github.com  -n github_qr.jpg   -d .../paths/
```

#### Artistic QR-Code

![](https://github.com/x-hw/amazing-qr/blob/master/example/1.png)![](https://github.com/x-hw/amazing-qr/blob/master/example/2.png)

```python
amzqr https://github.com -p logo.jpg -c
```

#### Animated GIF QR-Code

![](https://github.com/x-hw/amazing-qr/blob/master/example/daftpunktocat-guy_qrcode.gif)![](https://github.com/x-hw/amazing-qr/blob/master/example/daftpunktocat-guy_qrcode0.gif)

The only difference from Artistic QR-Code mentioned above is that you should input an image file in the `.gif` format. The you can get your black-and-white or colorful qr-code. Remember that when you use `-n` to customize the output-filename, then the output-filename must end by `.gif`.

## Tips

* Use a nearly **square** picture instead of a rectangle one.

* If the size of the picture is large, you should also choose a **rightly** large `-v` instead of using the default one.

* If part of the picture is transparent, the qr code will look like: ![](https://github.com/x-hw/amazing-qr/blob/master/example/aa.png)

  You can change the transparent layer to white, and then it will look like: ![](https://github.com/x-hw/amazing-qr/blob/master/example/a0.png)


