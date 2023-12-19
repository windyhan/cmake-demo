

# 子项目的源文件
aux_source_directory(./ SRC) 

# 子项目的静态库
add_library(cacl STATIC ${SRC})
