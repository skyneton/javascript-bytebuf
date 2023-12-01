# javascript-bytebuf
```javascript
const buf = new ByteBuf();
buf.writeVarInt(1234);
buf.writeString("TEST");
const readBuf = new ByteBuf(buf.flush());
print(readBuf.readVarInt(), readBuf.readString());
```
