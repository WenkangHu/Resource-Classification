1. 从官网获取下载命令，例如：conda install pytorch==1.1.0 torchvision==0.3.0 cudatoolkit=10.0 -c pytorch

   跳过无法下载的包（如：pytorch,mkl,torchvision...）

   **这一步除了那些无法下载的包，其他下载好的依赖包可以在之后的单独安装过程中安装**

2. conda install cudatoolkit=版本

3. conda install cudnn=版本

4. 单独下载之前无法下载的包的wheel，用pip离线安装

5. 单独安装其他缺失的包

6. 好用的镜像源：

   - -i https://pypi.douban.com/simple
   - 
