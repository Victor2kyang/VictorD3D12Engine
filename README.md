项目设置：

Configuration 设置成 ALL Configurations 
项目右键properties -> c/c++ -> General -> Multi-processor Compilation -> Yes //打开多处理器编译

Optimization -> Favor Size Or Speed -> Favor fast code 



Configuration 设置成 Release

Preprocessor -> Preprocessor Definitions -> 后面加上 ;NDEBUG //在release模式下定义NDEBUG 以区分debug模式和其他模式的编译

C/C++ -> Code Generation -> RuntimeLibrary -> Multi-threaded(/MT) //运行时库链接到静态库，让exe文件不再需要其他依赖可以直接运行