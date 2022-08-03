# qrCode-js
QrCode js

Support node v18

## Include

import { QRCode } from './qrcode';

```
new QRCode(document.getElementById("qrcode"), {
	text: "http://jindo.dev.naver.com/collie",
	width: 128,
	height: 128,
	colorDark : "#000000",
	colorLight : "#ffffff",
	correctLevel : QRCode.CorrectLevel.H
});
```

```
qrcode.clear(); // clear the code.
qrcode.makeCode("http://naver.com"); // make another code.
```
