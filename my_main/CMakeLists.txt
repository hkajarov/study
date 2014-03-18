include_directories("${PROJECT_SOURCE_DIR}/my_lib")
add_executable(summator main.c)
target_link_libraries(summator my_lib)

