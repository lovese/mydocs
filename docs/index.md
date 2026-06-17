site_name: 我的文档站
site_author: 老大

theme:
  name: material
  language: zh          # 中文
  palette:
    - scheme: default
      primary: indigo
      toggle:
        icon: material/brightness-7
        name: 切换到暗色
    - scheme: slate
      primary: indigo
      toggle:
        icon: material/brightness-4
        name: 切换到亮色
  features:
    - navigation.instant    # 即时加载（不刷新页面）
    - navigation.tracking   # URL 跟踪锚点
    - navigation.tabs       # 顶部导航标签
    - navigation.top        # 返回顶部按钮
    - search.suggest        # 搜索建议
    - search.highlight      # 搜索高亮

nav:
  - 首页: index.md
  - 使用指南: guide.md
  - API 文档: api.md


