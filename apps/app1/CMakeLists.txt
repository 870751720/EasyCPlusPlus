find_package(Boost REQUIRED)

add_executable(app1 src/main.cpp)
target_link_libraries(app1 PRIVATE Boost::boost)
