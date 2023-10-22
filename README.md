# ProtoSpecs

## Compiling

### NanoPB

Install either Python 3 or 2 and run the following command to install the dependencies:

```bash
pip install --upgrade grpcio-tools
```

### Usage

```bash
mkdir build/nanopb
cd src
python ../generators/nanopb/generator/protoc --proto_path=generators/nanopb *.proto --nanopb_out=../build/nanopb
```

## Helpful Resources for debugging

<https://protobuf-decoder.netlify.app/>  
<https://protogen.marcgravell.com/>

```bash
protoc --decode_raw < test.bin
```
