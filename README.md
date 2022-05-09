# QRCODE_GMAIL
import pyqrcode
from pyqrcode import QRCode

# String which represent the QR code
s = "lambadetarunkumar1997@gmail.com"

# Generate QR code
url = pyqrcode.create(s)

# Create and save the png file naming "myqr.png"
url.svg("my gmail.svg", scale=8)
