
# opencv配置
### 1.下载opencv，opencv无需安装，只需要解压
### 2.系统环境变量中添加    *\build\x64\vc15\bin
### 3.VS中新建空项目，项目->项目属性
#### (1)VC++目录->包含目录，添加 *\build\include 和 *\build\include\opencv2

#### (2)VC++目录->库目录，添加 *\build\x64\vc15\lib

#### > (3)链接器->输入->附加依赖项，添加 opencv_world\*\*\*d.lib 和 opencv_world\*\*\*d.lib（d表示debug）

#### > (4)如果碰到“fatal error LNK1104：无法打开文件“opencv_world\*\*\*d.lib”，链接器->常规->附加器目录，添加 *\build\x64\vc15\lib

### ***以上星号内容均为视具体情况***
