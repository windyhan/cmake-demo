project(main)

#主项目文件
aux_source_directory(${PROJECT_SOURCE_DIR}/src SRC)
include_directories(${PROJECT_SOURCE_DIR}/include)

#添加子项目目录
add_subdirectory(cacl)

#链接子项目的静态库
link_libraries(cacl)

#主项目可执行文件
add_executable(main ${SRC})

