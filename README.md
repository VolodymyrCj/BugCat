# BugCat
功能：获取被动bug(程序异常崩溃)和主动bug（手动提交），提交到服务器。

特点：
1：一个bug一个bug的上传，而不是批量上传
2：重复bug不会重复上传，即使上传bug过程中，程序突然崩溃，下次会继续上次的上传

注意：服务器需实现逻辑（唯一的请求）：将获取到的index原样返回即可。
