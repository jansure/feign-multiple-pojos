# feign-multiple-pojos
a demo supports mutiple pojos and file arrs with FeignClient's default Contract by rewrting form-encoder .使用feign自带Contract，通过重写编码器支持多个pojo与多文件传输。

文件上传demo,用了三个文件夹 D:\testFile, D:\testFile\producer, D:\testFile\temp写死了三个文件夹用于测试，手动在电脑中建立一下。Mac自己改一下路径。

最重要的配置都在config目录下。

Feign默认是不支持多实体传输的。
这里有两点注意，一是feign默认是采用
SpringMvcContract。我们需要声明为feign.contract.default();
这样例子中的编码器才会生效。
具体的调用示例见代码
详细教程参加我的博客 https://blog.csdn.net/qq_34523427/article/details/88863800
