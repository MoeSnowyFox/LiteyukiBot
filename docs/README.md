---
home: true
icon: home
title: 首页
heroImage: https://cdn.liteyuki.icu/static/img/logo.png
bgImage:
bgImageDark:
bgImageStyle:
  background-attachment: fixed
heroText: LiteyukiBot
tagline: 轻雪机器人，一个以轻量和简洁为设计理念基于Nonebot2的OneBot标准聊天机器人

actions:
  - text: 快速部署
    icon: lightbulb
    link: ./deployment/install.html
    type: primary

  - text: 使用手册
    icon: book
    link: ./usage/basic_command.html

highlights:

  - header: 简洁至上
    image: /assets/image/layout.svg
    bgImage: https://theme-hope-assets.vuejs.press/bg/2-light.svg
    bgImageDark: https://theme-hope-assets.vuejs.press/bg/2-dark.svg
    bgImageStyle:
      background-repeat: repeat
      background-size: initial
    features:
      - title: 基于Nonebot2
        icon: robot
        details: 拥有良好的生态支持
        link: https://nonebot.dev/

      - title: 可视化插件管理
        icon: plug
        details: 使用<code>npm</code>，无需命令行操作即可安装/卸载插件

      - title: 点击交互
        icon: mouse-pointer
        details: 新的点击交互模式，拒绝手打指令

      - title: 主题支持
        icon: paint-brush
        details: 支持多种主题，可自定义资源包，满足你的审美需求

      - title: 国际化
        icon: globe
        details: 支持多种语言，包括i18n部分语言和自行扩展的语言代码
        link: https://baike.baidu.com/item/i18n/6771940

      - title: 简易配置
        icon: cog
        details: 无需过多配置，开箱即用
        link: https://bot.liteyuki.icu/deployment/config.html

      - title: 低占用
        icon: memory
        details: 使用更少的依赖和资源

      - title: OneBot标准
        icon: link
        details: 支持OneBotv11/12标准的四种通信协议
        link: https://onebot.dev/

      - title: Alconna命令解析
        icon: link
        details: 使用Alconna实现高效命令解析
        link: https://github.com/nonebot/plugin-alconna

      - title: 便捷更新
        icon: cloud-download
        details: 聊天窗口命令更新，无需手动下载

      - title: 服务支持
        icon: server
        details: 内置轻雪API，可自动收集错误，提供图床服务

      - title: 开源
        icon: code
        details: 项目遵循MIT协议开源，欢迎各位的贡献

  - header: 快速部署
    image: /assets/image/box.svg
    bgImage: https://theme-hope-assets.vuejs.press/bg/3-light.svg
    bgImageDark: https://theme-hope-assets.vuejs.press/bg/3-dark.svg
    highlights:
      - title: 安装 Git 和 Python3.10+
      - title: 使用 <code>git clone https://github.com/snowykami/LiteyukiBot</code> 以克隆项目至本地。
        details: 如果无法连接到GitHub，可以使用 <code>git clone https://gitee.com/snowykami/LiteyukiBot</code>。
      - title: 使用 <code>cd LiteyukiBot</code> 切换到项目目录。
      - title: 使用 <code>pip install -r requirements.txt</code> 安装项目依赖。
        details: 如果你有多个 Python 环境，请使用 <code>pythonx -m pip install -r requirements.txt</code>。
      - title: 使用 <code>python main.py</code> 启动项目。
copyright: © 2021-2024 SnowyKami All Rights Reserved
---