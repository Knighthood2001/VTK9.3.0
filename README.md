适配PCL1.14.0+Qt5.15.2+VTK9.3.0的VTK，是放到C:\Program Files\PCL 1.14.0\3rdParty\VTK目录下的适配文件。

上传后提示

remote: warning: See https://gh.io/lfs for more information.
remote: warning: File bin/vtkCommonCore-9.3d.dll is 52.69 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
remote: warning: GH001: Large files detected. You may want to try Git Large File Storage - https://git-lfs.github.com.

也就是说，漏了这个dll文件，导致VTK无法正常使用。

因此我把全部文件放到网盘中了，方便大家下载。

链接：https://pan.quark.cn/s/7dea9939f5f6