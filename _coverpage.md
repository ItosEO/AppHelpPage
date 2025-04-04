<div class="cover-logo-placeholder">
  <span>📚</span>
</div>

# **用户手册**

> vivo温控引擎 与 系统优化Pro

* ✓ 功能介绍
* ✓ 使用说明
* ✓ 常见问题

<p class="buttons">
  <a href="https://fk.qkrxr.cn/shop/itostar" target="_blank" class="button">获取卡密</a>
  <a href="https://down.itostar.com.cn/PremiumApp" target="_blank" class="button">网盘</a>
  <a href="#/温控" class="button primary">开始阅读</a>
</p>

<style>
  /* 移除 Docsify 默认的封面背景 */
  .cover::before {
    background: none !important;
  }

  .cover {
    /* 使用渐变背景 */
    background: linear-gradient(to bottom right, #c8e6c9, #a5d6a7); /* 浅绿色渐变 */
    min-height: 100vh; /* 确保覆盖整个视口高度 */
    display: flex; /* 使用 Flexbox 布局 */
    flex-direction: column; /* 允许内容垂直排列 */
    align-items: center; /* 水平居中 */
    justify-content: center; /* 垂直居中 */
    text-align: center;
    padding: 20px;
    box-sizing: border-box;
    position: relative;
    z-index: 1;
  }

  /* 针对 Docsify 生成的主要内容区域 */
  .cover section.cover-main {
    color: #333;
    max-width: 600px;
    width: 90%; /* 适应不同宽度 */
    margin: 20px auto; /* 上下边距，左右自动 */
    padding: 20px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 15px;
    backdrop-filter: blur(2px);
    -webkit-backdrop-filter: blur(2px);
    /* 确保 z-index 高于背景伪元素 */
    position: relative;
    z-index: 2;
  }

  /* Logo 占位符样式 (独立于 .cover-main) */
  .cover-logo-placeholder {
    font-size: 60px;
    margin-bottom: 20px;
    line-height: 1;
    /* 确保 Logo 在内容区上方（如果需要） */
     order: -1; /* Flexbox 顺序，让它排在前面 */
     margin-top: 5vh; /* 距离顶部一些距离 */
  }

  /* 标题样式 (针对 Markdown 解析后的 h1) */
  .cover section.cover-main > h1 {
    color: #1b5e20;
    font-size: 2.5em !important;
    margin: 0.5em 0 !important;
    font-weight: bold !important;
    border-bottom: none !important;
  }

  /* 副标题样式 (针对 Markdown 解析后的 blockquote > p) */
  .cover section.cover-main > blockquote > p {
    margin: 1em 0 !important;
    font-size: 1.1em !important;
    color: #424242 !important;
  }

  /* 列表样式 (针对 Markdown 解析后的 ul) */
  .cover section.cover-main > ul {
    list-style: none !important;
    padding: 0 !important;
    margin: 1.5em 0 !important;
  }

  /* 列表项样式 (针对 Markdown 解析后的 li) */
  .cover section.cover-main > ul > li {
    display: inline-block !important;
    margin: 0 15px !important;
    font-size: 1em !important;
    color: #555 !important;
  }

  /* --- 按钮样式调整 --- */
  /* 按钮容器样式 (直接针对 .cover 下的 .buttons) */
  .cover p.buttons {
      margin-top: 2.5em !important;
      /* 确保按钮容器也在 Flex 布局流中正确处理 */
       width: 100%;
       order: 1; /* Flexbox 顺序，让它排在内容区之后 */
       margin-bottom: 5vh; /* 距离底部一些距离 */
  }

  /* 按钮通用样式 (直接针对 .cover 下的 .button) */
  .cover .button {
    display: inline-block;
    text-decoration: none !important;
    color: #333;
    border: 1px solid #aaa;
    padding: 12px 25px;
    border-radius: 25px;
    margin: 5px 10px; /* 增加垂直间距以防换行 */
    font-size: 1em;
    transition: all 0.3s ease;
    background-color: rgba(255, 255, 255, 0.3);
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
    cursor: pointer; /* 添加指针样式 */
  }

  /* 按钮悬停效果 (直接针对 .cover 下的 .button) */
  .cover .button:hover {
    background-color: rgba(255, 255, 255, 0.6);
    border-color: #888;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    color: #111;
  }

  /* 主要按钮样式 (直接针对 .cover 下的 .button.primary) */
  .cover .button.primary {
    background-color: #4caf50;
    border-color: #4caf50;
    color: white !important;
  }

  /* 主要按钮悬停效果 (直接针对 .cover 下的 .button.primary) */
  .cover .button.primary:hover {
    background-color: #43a047;
    border-color: #43a047;
    color: white !important;
  }
  /* --- 按钮样式调整结束 --- */


  /* 移除 Docsify 可能添加的 footer */
  .cover footer {
      display: none !important;
  }

</style>
