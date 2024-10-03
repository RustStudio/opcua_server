![Cargo build](https://github.com/RustStudio/opcua_server/actions/workflows/build.yaml/badge.svg) ![Cargo test](https://github.com/RustStudio/opcua_server/actions/workflows/test.yaml/badge.svg) ![Cargo format](https://github.com/RustStudio/opcua_server/actions/workflows/format.yaml/badge.svg)

# OPC-UA server template

# Usage
```
cargo run
```

# Test scripts
## address_space.py
This script is to help you get the addresses from your OPC-UA server

## opcua_client.py
This script uses the `opcua-asyncio` python package to run a simple client example.
The reason for this approach is to encourage interoperability between different languages instead of having both client and server in Rust.