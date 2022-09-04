cmake_minimum_required(VERSION 3.14)

project(helloworld)

SET(CMAKE_EXE_LINKER_FLAGS "${CMAKE_EXE_LINKER_FLAGS} -static")

add_executable(${PROJECT_NAME}
    "main.cpp"
)
/opt/gnuradio
target_link_libraries(${PROJECT_NAME} gnuradio-runtime gnuradio-audio gnuradio-analog)

