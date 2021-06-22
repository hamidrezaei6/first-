# first-
import pyqrcode as pq
mc = input('enter txt for create QR Code : ')
myCode = pq.create(mc)
myCode.svg('code.svg', scale=8)


print('Done...')
input()cls
