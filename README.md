# hexo-theme-shokaX
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fzkz098%2Fhexo-theme-shokaX.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fzkz098%2Fhexo-theme-shokaX?ref=badge_shield)
![LICENSE](	https://img.shields.io/github/license/zkz098/hexo-theme-shokaX)
![stars](https://img.shields.io/github/stars/zkz098/hexo-theme-shokaX)
![version](https://shields.io/npm/v/hexo-theme-shokax)

此项目是shoka的一个二次开发版(算精神续作),致力于提高性能和优化魔改体验 \
诞生原因是目前shoka已经两年没有更新了,积压了大量BUG和功能请求。\
本项目处于高强度开发期,但github仓库版本已基本可用 \
二次开发与常见问题请看wiki

## 待办名单
- [x] 推出一个可用的测试版
- [x] 支持twikoo和waline评论系统
- [x] 优化部分html标签
- [x] 原生PWA支持
- [x] 注入js和css支持
- [x] 自定义font
- [x] 部分功能调整为可关闭
- [ ] 重构lib方法(长期计划)
- [ ] 异步化js

## 和shoka的区别
原先shoka使用了javascript+Native+nunjucks的技术 \
而shokaX则使用了typescript+Vue 3+Pug的技术搭配 \
图标库可能会更换为Font Awesome 6 \
更改了大量难以访问的CDN链接

## 如何安装?
建议使用[ShokaX-CLI](https://github.com/zkz098/shokaX-CLI) ,执行下列命令即可:
```bash
npm i shokax-cli --location=global
# hexo init 初始化环境
SXC install shokaX
```

# 许可证
许可证: MIT \
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fzkz098%2Fhexo-theme-shokaX.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fzkz098%2Fhexo-theme-shokaX?ref=badge_large)

# 致谢名单
## 开源项目
| 名称               | 作者                | 描述                 |
|:-----------------|:------------------|:-------------------|
| Hexo             | Hexo contributors | 为本项目提供了良好的基础       |
| hexo-theme-shoka | amehime           | 本项目的父主题            |

## 贡献者
| 名称         | 站点                         | 描述                     |
|:-----------|:---------------------------|:-----------------------|
| Lavender   | https://www.lavenderdh.cn/ | 提供了大量shoka主题的魔改        |
| AdminZhang | https://www.a9-9.top/      | 为本项目提供了大量想法并进行了DEBUG工作 |

