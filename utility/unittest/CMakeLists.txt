#set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})

add_test_snippet(serialize_test utility)
add_test_snippet(serialization_adapters_test utility)
add_dependencies(serialization_adapters_test core)
target_link_libraries(serialization_adapters_test core)
add_test_snippet(shared_data_test utility)
add_test_snippet(logger_test utility)
add_dependencies(logger_test core)
target_link_libraries(logger_test core)
add_test_snippet(reactor_test utility)
add_test_snippet(asyncevent_test utility)
add_test_snippet(tcpserver_test utility)
add_test_snippet(tcpclient_test utility)
add_test_snippet(timer_test utility)
add_test_snippet(address_test utility)
add_test_snippet(channel_test utility)
add_test_snippet(config_test utility)
add_test_snippet(bridge_test utility)
add_test_snippet(ssl_test utility)
add_test_snippet(proxy_test utility)
