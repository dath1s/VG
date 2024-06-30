project(TestProject)
add_executable(project1 main.cpp)
install(TARGETS project1 DESTINATION ${CMAKE_CURRENCT_SOURCE_DIR}/_bin)