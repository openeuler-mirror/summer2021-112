# 项目进度

* 学习阶段：

  * 通过阅读源码，技术文档，相关论文（Qemu和VirtIO），动手实践等方式对Qemu和LibFuzzer进行了学习
  * 根据自己学习心得，发布了三篇博客
    * OpenEuler远程环境搭建：https://blog.csdn.net/weixin_42733202/article/details/119716461
    * LibFuzzer学习：https://blog.csdn.net/weixin_42733202/article/details/119715246
    * Qemu Fuzzer学习：https://blog.csdn.net/weixin_42733202/article/details/119715287
  * 复现了使用LibFuzzer框架发现的Qemu漏洞CVE-2017-12809，过程记录在博客中
  * 构建了用于学习Qemu Fuzzer的Docker环境：https://hub.docker.com/repository/docker/cascadessjtu/qemu_fuzz
  * 整理了一些文档资料
* 实践阶段：
  * 搭建了OpenEuler系统云主机的开发环境
  * 加入了Qemu Mailing List，学习了向上游社区提交代码的方法
  * 对AArch64进行适配（未完成）

# 仓库介绍
仓库为qemu-2.10版本的代码，是我用于复现漏洞的版本
项目用到的为qemu-6.0
