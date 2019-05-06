# -VPS-

1. 将 “/etc/yum.repos.d” 目录下的所有*.repo 文件全部删除。
2. 拷贝上面 “Centos-7.repo” 文件到此文件夹下
3. 清理yum 缓存：
  yum clean all
  yum makecache

