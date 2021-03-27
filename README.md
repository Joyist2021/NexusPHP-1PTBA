# NexusPHP

[![license][license-img]][github] [![web][web-img]][web] [![github][github-img]][github]

[![codecov](https://codecov.io/gh/tgbot-collection/YYeTsBot/branch/master/graph/badge.svg?token=ZL1GCIF95D)](https://github.com/Joyist2021/NexusPHP-1PTBA)

**⚠️⚠️A modern HTTP web server index for Apache httpd, lighttpd, and nginx.


## Important

* Do **not** install any files from the `src` folder, they need to be
  preprocessed to work correctly!
* Find a preprocessed package and detailed install instructions on the
  [project page][web].
* For bug reports and feature requests please use [issues][github-issues].


## Build

ABOUT NexusPHP
This Project NexusPHP is an open-sourced private tracker script written in PHP.
It forks from the TBSource project and some other open-sourced projects.
Please read the LICENSE file before using this project.
Read the INSTALL file for information about how to use it.
Read the RELEASENOTE file about this release.
Visit http://www.nexusphp.com for more information about this project.

forked from cdwolfling/NexusPHP

add config/allconfig.php to ignorelist, you can get it back from https://github.com/cdwolfling/NexusPHP/commit/0f3742a86c8afae4c2a7f9ccd1549c877120a606

## TODO List
- [ ] Enhance progress bar
  - [x] Add progress bar
  - [ ] Show seed or leech detail in progress bar
- [ ] Enhance offer area
  - [ ] Add lock option for offer
  - [ ] Add small description to offer detail
  - [ ] Add rules description to offer head
- [x] Add big torrent promotion option
- [ ] Add notice area in head
- [ ] Move sign in to top
- [x] Auto hide empty donate string

## 主要文件目录结构:
```
├── NexusPHP-1PTBA
    ├── attachments    # 上传截图
    ├── bitbucket      # 上传用户头像
    ├── config
        └── allconfig.php         # 配置
    ├── include
        ├── functions.php     # 全局函数
        └── cleanup.php       # 清理脚本
    ├── lang          # 语言
    ├── subs          # 字幕文件
    ├── torrents      # 种子储存目录
    ├── docleanup.php     # 清理
    ├── forums.php      # 论坛
    ├── invite.php      # 邀请
    ├── shoutbox.php    # 消息框
    ├── usercp.php      # 用户控制面板
    ├── upload.php      # 发布
    ......
```

# 支持我

觉得本项目对你有帮助？你可以通过以下方式表达你的感受：

* 感谢字幕组
* 点一个star🌟和fork🍴
* 宣传，使用，提交问题报告
* 收藏[网站](https://1ptba.com/)
* [Telegram Channel](https://t.me/1ptba)
* 捐助我，[给我买杯咖啡？](https://1ptba.com/donate.php)
* 捐助我，[爱发电？](https://1ptba.com/donate.php)

# 感谢
[Thanks](THANKS.md)

[MIT](LICENSE)
## License

The MIT License (MIT)

Copyright (c) 2020 (1PTBA)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.



[web]: https://1ptba.com/
[github]: https://github.com/Joyist2021/NexusPHP-1PTBA
[github-issues]: https://github.com/Joyist2021/NexusPHP-1PTBA/issues
[release]: https://github.com/Joyist2021/NexusPHP-1PTBA/releases
[develop]: https://github.com/Joyist2021/NexusPHP-1PTBA/develop/
[node]: https://nodejs.org
[material-design-icons]: https://github.com/google/material-design-icons

[license-img]: https://img.shields.io/badge/license-MIT-a0a060.svg?style=flat-square
[web-img]: https://img.shields.io/badge/web-1ptba.com-a0a060.svg?style=flat-square
[github-img]: https://img.shields.io/badge/github-Joyist2021/NexusPHP-a0a060.svg?style=flat-square
