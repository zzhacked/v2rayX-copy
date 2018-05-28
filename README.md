
本项目基于v2rayX原版的编译,因为有时候原作者并没有发布编译好的.app，供没法编译的小伙伴使用!

编译方法：

1、为终端设置全局代理：
  export ALL_PROXY=socks5://127.0.0.1:1080 设置后运行curl ip.cn查看是否成功。
  注：我是用的socks5代理，所以此处配置并根据实现的代理方式来配置
  
2、运行：
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/Cenmrev/V2RayX/master/compilefromsource.sh)"
  
3、执行完以上2步就编译成功

4、再次感谢原作者的努力，才有我等屁民使用的权利!
