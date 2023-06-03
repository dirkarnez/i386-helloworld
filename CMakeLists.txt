project("i386-linux-helloworld")

set(CMAKE_SYSTEM_PROCESSOR i386)
set(CMAKE_SYSTEM_NAME Linux)
set(CMAKE_SYSTEM_VERSION gnu)

set(CMAKE_C_FLAGS "-m32")
set(CMAKE_CXX_FLAGS "-m32")

add_executable(${PROJECT_NAME} 
    "src/main.cpp")
