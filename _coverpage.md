<div class="cover-main">
  <div class="cover-logo-placeholder">
     <span>📚</span>
  </div>

  <h1>用户手册</h1>
  <p>vivo 温控引擎与系统优化 Pro</p>
  <ul>
    <li>✓ 功能介绍</li>
    <li>✓ 使用说明</li>
    <li>✓ 常见问题</li>
  </ul>
  <p class="buttons">
    <a href="#/温控" class="button primary">开始阅读</a>
    <a href="https://fk.qkrxr.cn/shop/itostar" target="_blank" class="button">获取卡密</a>
  </p>
</div>

<div class="cover-footer-spacer"></div>

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
    align-items: center; /* 垂直居中 */
    justify-content: center; /* 水平居中 */
    text-align: center;
    padding: 20px;
    box-sizing: border-box;
  }

  .cover-main {
    color: #333; /* 深灰色文字，对比度更好 */
    max-width: 600px;
    margin: auto; /* 确保内容块居中 */
  }

  /* Logo 占位符样式 */
  .cover-logo-placeholder {
    font-size: 60px; /* 调整图标大小 */
    margin-bottom: 20px;
    line-height: 1;
  }
  /* 如果使用图片 Logo */
  /*
  .cover-main img {
    width: 100px;
    margin-bottom: 20px;
  }
  */

  .cover-main h1 {
    color: #1b5e20; /* 深绿色标题 */
    font-size: 2.5em; /* 调整标题大小 */
    margin: 0.5em 0;
    font-weight: bold;
    /* 注意：这里会继承你在 index.html 中设置的 'BC Font' */
    /* 如果想用特定字体，可以在这里重新指定 font-family */
  }

  .cover-main p {
    margin: 1em 0;
    font-size: 1.1em;
    color: #424242; /* 稍深的灰色 */
  }

  .cover-main ul {
    list-style: none;
    padding: 0;
    margin: 1.5em 0;
  }

  .cover-main li {
    display: inline-block; /* 横向排列 */
    margin: 0 15px;
    font-size: 1em;
    color: #555;
  }

  .cover-main .buttons {
    margin-top: 2.5em;
  }

  .cover-main .button {
    display: inline-block;
    text-decoration: none;
    color: #333;
    border: 1px solid #aaa; /* 默认按钮边框 */
    padding: 12px 25px;
    border-radius: 25px; /* 圆角按钮 */
    margin: 0 10px;
    font-size: 1em;
    transition: all 0.3s ease;
    background-color: rgba(255, 255, 255, 0.3); /* 半透明白色背景 */
    backdrop-filter: blur(5px); /* 毛玻璃效果 (部分浏览器支持) */
    -webkit-backdrop-filter: blur(5px);
  }

  .cover-main .button:hover {
    background-color: rgba(255, 255, 255, 0.6);
    border-color: #888;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }

  .cover-main .button.primary {
    background-color: #4caf50; /* 主按钮绿色背景 */
    border-color: #4caf50;
    color: white; /* 白色文字 */
  }

  .cover-main .button.primary:hover {
    background-color: #43a047; /* 主按钮悬停深一点的绿色 */
    border-color: #43a047;
    color: white;
  }

  /* 增加一个底部空白区域，避免内容紧贴底部 */
  .cover-footer-spacer {
      height: 5vh; /* 视口高度的 5% */
  }

  /* 覆盖你在 index.html 中设置的全局字体 (如果需要) */
  /*
  .cover-main, .cover-main h1, .cover-main p, .cover-main li, .cover-main .button {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif !important;
  }
  */

</style>
