# cardreader-acr122u
A Driver that reads tags from acr122u via libnfc and emits on WebSocket Server

uid: '04:c3:1b:22:6b:52:84',
data: <Buffer 04 b8 f0 c4 22 6b 52 80 9b 48

data: <Buffer 04 c3 1b 54 22 6b 52 84 9f 48
'04 b8 f0 c4 22 6b 52 80 9b 48', 'hex'

'04 b8 f0 c4 22 6b 52 80 9b 48'.replace(/ /g,''
console.log(new Buffer('04 b8 f0 c4 22 6b 52 80 9b 48'.replace(/ /g,''), 'hex').toString())
���"kR��H
console.log(new Buffer('04 b8 f0 c4 22 6b 52 80 9b 48'.replace(/ /g,''), 'hex').toString('ASCII'))
8pD"kR