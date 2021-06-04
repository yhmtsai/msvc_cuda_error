project(HelloCuda LANGUAGES CXX)

enable_language(CUDA)
add_executable(hello hello.cu)
message("CMAKE_GENERATOR ${CMAKE_GENERATOR}")
mwssage("CMAKE_GENERATOR_TOOLSET ${CMAKE_GENERATOR_TOOLSET}")
