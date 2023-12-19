cmake_minimum_required(VERSION 3.12)

# 子项目的源文件
aux_source_directory(./ SRC) 

# 子项目的静态库生成
add_library(${LIB_CACL} STATIC ${SRC})

