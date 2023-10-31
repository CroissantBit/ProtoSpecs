# ProtoSpecs

## Compiling

All projects that depend on this repo should pull the latest version and then compile .proto using its own compiler.

## Helpful Resources for debugging

<https://protobuf-decoder.netlify.app/>  
<https://protogen.marcgravell.com/>

```bash
protoc --decode_raw < test.bin
```
