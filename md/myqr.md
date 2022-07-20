### MYQR | QR Code scanner for login hotspot MikroTik

#### Cara pakai

1. Tambahkan button di login.html

```html
<button onclick="window.location='https://fauzan-cell.github.io/myqr';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.

```
/ip hotspot walled-garden ip
add action=accept comment="QR Code Scanner" disabled=no dst-host=fauzan-cell.github.io

```
3. Centang HTTP PAP di hotspot server profile.

![HTTPS PAP MikroTik](./img/myqr-http-pap.png "HTTPS PAP MikroTik")

>_QR Code Scanner hanya bisa dipakai pada browser yang memiliki hak akses kamera._

<div>
	<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
	<!-- ads3 -->
	<ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-1716315177239884" data-ad-slot="4095402072"
	 data-ad-format="auto" data-full-width-responsive="true"></ins>
	<script>
		(adsbygoogle = window.adsbygoogle || []).push({});
	</script>
</div>


![MYQR | QR code scanner](./img/myqr.jpg "MyQR | QR code scanner")


Powered by [webqr.com](//webqr.com)

