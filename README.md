# DCB USD Chain

## Initial setup
1. Git clone
2. Build
3. Run!

## Build instruction
* WASM_BUILD_TOOLCHAIN=nightly-2020-10-06 cargo build --release

## Run instruction
* Execute 
  ```
 ./target/release/node-template \
  --base-path /root/nodeName \
  --chain ./customRaw.json \
  --port 30333 \
  --ws-port 9944 \
  --rpc-port 9933 \
  --telemetry-url 'wss://telemetry.polkadot.io/submit/ 0' \
  --validator \
  --rpc-methods Unsafe \
  --name NodeName \
  --bootnodes /ip4/<IP Address>/tcp/<Port>/p2p/<Peer ID>
  ```
