cmake_minimum_required(VERSION "2.8.12.2")

project("Helloworld")

#include_directories(./code)

add_executable("${PROJECT_NAME}" "hello.cpp")
#link_libraries(Helloworld codefun)

#install(TARGET "${PROJECT_NAME}" DESTINATION bin)
#install(FILES "hello.cpp" DESTINATION src)

