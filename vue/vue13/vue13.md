1.移动端项目的调试（运行在手机端的浏览器上）
  pc 项目就是电脑浏览器运行 调试工具就是开发者工具
  真机调试 放在真实的设备上进行调试 
  1. 将手机和电脑连接到同一局域网
  2. 在手机上输入项目的地址
  3. 调试 安卓 谷歌   ios safri浏览器
  4. usb 连接电脑 
  5. 用手机的safri浏览器打开项目
2.自动播放bug
  ios 系统限制音频和视频的自动播放 手动播放就可以
3.刷新404 
  打包路径 默认的根路径
  上传到www/html  不带dist目录
  照着文档去修改配置文件
4.gzip压缩
  a.本地打包的时候产生gzip压缩文件
  b.nginx 服务器配置 开启gzip压缩
5.提升用户体验 
  在加载等待时间添加过度动画