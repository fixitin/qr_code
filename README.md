![Tux, Logo](logo.png)

## An application to generate qr code from web view. Made with fastapi.

## Steps:
Install fast api:
<ul>
  <li>pip install fastapi</li>
  <li>pip install "uvicorn[standard]"</li>
</ul>

Install qrcode library ( version 7.4.2 )
<ul>
  <li>pip install qrcode</li>
</ul>

## An easy way to generate a sample qr

```
import qrcode
img = qrcode.make('Hello my dear')
type(img)  # qrcode.image.pil.PilImage
img.save("my_dear.png")
```

