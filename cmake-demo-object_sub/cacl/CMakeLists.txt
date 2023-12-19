cmake_minimum_required(VERSION 2.8.12)

aux_source_directory(. CACL_SRC)

# 子项目的静态库生成
add_library(SubProjectObjectLibrary OBJECT ${CACL_SRC})

