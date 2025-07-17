add_executable(executable ./src/main.cpp)
target_link_libraries(executable PUBLIC Library)
target_include_directories(executable PUBLIC ./include/)
