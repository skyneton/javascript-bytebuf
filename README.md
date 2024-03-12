# javascript-bytebuf
```javascript
const buf = new ByteBuf();
buf.writeVarInt(1234);
buf.writeString("TEST");
const readBuf = new ByteBuf(buf.flush());
console.log(readBuf.readVarInt(), readBuf.readString());
```
