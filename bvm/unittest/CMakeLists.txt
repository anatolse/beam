add_test_snippet(shaders_test bvm)

configure_file("../Shaders/vault/contract.wasm" "${CMAKE_CURRENT_BINARY_DIR}/vault/contract.wasm" COPYONLY)
configure_file("../Shaders/vault/app.wasm" "${CMAKE_CURRENT_BINARY_DIR}/vault/app.wasm" COPYONLY)
configure_file("../Shaders/dummy/contract.wasm" "${CMAKE_CURRENT_BINARY_DIR}/dummy/contract.wasm" COPYONLY)
configure_file("../Shaders/oracle/contract.wasm" "${CMAKE_CURRENT_BINARY_DIR}/oracle/contract.wasm" COPYONLY)
configure_file("../Shaders/StableCoin/contract.wasm" "${CMAKE_CURRENT_BINARY_DIR}/StableCoin/contract.wasm" COPYONLY)
configure_file("../Shaders/faucet/contract.wasm" "${CMAKE_CURRENT_BINARY_DIR}/faucet/contract.wasm" COPYONLY)
