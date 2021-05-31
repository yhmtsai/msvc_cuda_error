project(HelloCuda LANGUAGES CXX)

enable_language(CUDA)
add_executable(hello hello.cu)
