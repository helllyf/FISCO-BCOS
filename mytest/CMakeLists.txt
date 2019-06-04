cmake_minimum_required(VERSION  2.8)
project(HELLOWORLD)
#包含原程序,即把给定目录下的源程序复制给变量DIR_SRC
aux_source_directory(./ DIR_SRC)

#生成程序
add_executable(helloworld ${DIR_SRC})
