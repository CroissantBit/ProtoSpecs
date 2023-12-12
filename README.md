# ProtoSpecs

## Compiling

All projects that depend on this repo should pull the latest version and then compile .proto files using its own compiler.

## Packets

Each packet must be prefixed with a int16 that represents the message id.
See: [main.options](https://github.com/CroissantBit/ProtoSpecs/blob/main/src/main.options)

## Helpful Resources for debugging

<https://protobuf-decoder.netlify.app/>  
<https://protogen.marcgravell.com/>

```bash
protoc --decode_raw < test.bin
```
