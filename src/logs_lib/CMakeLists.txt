find_package(Boost COMPONENTS log system)
add_library(test_log INTERFACE)
target_link_libraries(test_log INTERFACE Boost::log Boost::system)
