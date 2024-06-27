# Note 240627
## Review

### BOM
- Window
  - `window.setInterval(fun,time);设置间隔调用` 在固定的时间间隔内执行指定程序
    - fun：在固定时间间隔内执行的程序函数。
    - time：固定时间间隔，单位为毫秒。
  - `window.clearInterval(number);取消间隔调用`
  - `Window.setTimeout(fun,time)` 延迟执行：在固定的时间间隔内执行指定程序
    - fun：在固定时间间隔内执行的程序函数。
    - time：固定时间间隔，单位为毫秒。
  - `window.clearTimeout(number);` 取消延迟执行
    - number 为 `Window.setTimeout()` 以及 `window.clearTimeout()` 的返回类型
  - `window.open("http://www.baidu.com","_self");` 打开新窗口
    - url：打开窗口对应的网页url。
    - target：打开方式。与href中的target一样，取值如下（_top,_self,_blank,_parent,frameName）。（默认值为_blank）
- location
  - host：设置或获取当前窗口地址的域名及端口。格式为127.0.0.1:8020。
  - hostname：设置或获取当前窗口地址的域名。格式为127.0.0.1。
  - protocol：设置或获取当前窗口地址的请求方式。格式为http:
  - port ：设置或获取当前窗口地址的端口。 格式为8020。
  - href:设置或获取当前窗口地址的全路径。最常用，一般用于网页刷新、网页跳转、网页参数的解析。
- history对象：对象表示窗口的历史记录对象。
  - 通用属性与方法
    - length：返回浏览器历史列表中的 URL 数量
    - back()：加载 history 列表中的前一个 URL路径。
    - forward()：加载 history 列表中的下一个 URL路径。
    - go(step)：加载 history 列表中的前/后step个URL路径，参数可以为负。
- for ... of 循环
- 默认值
- 箭头函数

### Web
- Servlet
  - Servlet是用Java编写的服务器端程序，其主要目的是处理客户端请求，执行某种业务逻辑，并生成响应。Servlet可以生成任何类型的数据，包括HTML，XML，JSON，图片，视频等。
- Jsp
  - JSP则是一个使用Java代码嵌入HTML的技术，主要用于创建动态的Web页面。JSP页面最终会被服务器转换（或说编译）成一个Servlet来处理请求。JSP的主要优点是可以将页面布局和设计与业务逻辑分离，使得Web开发人员可以更专注于页面的外观，而Java开发人员可以更专注于业务逻辑。
- C/S
- B/S
- Tomcat
  - 直接解压就能用
  - 目录