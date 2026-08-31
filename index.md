<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!-- SEO & 验证 -->
  <meta name="baidu-site-verification" content="codeva-92na2s5nOX" />
  <meta name="msvalidate.01" content="7DBB70AE4DFB4F1A76794977316FBB94" />
  <meta name='description' content='可爱小胖丨读博经验与讲师日常分享。机械工程博士，高校讲师，瑞幸咖啡常客，甜甜恋爱期待者。多平台分享读博科研干货和讲师日常生活的自媒体新兵蛋子。欢迎大家关注交流，但去莫复问，白云无尽时，一起加油。'>
  <meta http-equiv='content-language' content='zh-CN'>
  <title>可爱小胖丨读博经验与讲师日常分享</title>
  <link rel="icon" href="/calendar.webp">
  
  <style>
    /* 全局重置 */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      background: #f5f6f8;
      font-family: system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
      color: #222;
      line-height: 1.6;
    }

    .wrap {
      max-width: 880px;
      margin: 40px auto;
      padding: 0 20px;
    }

    /* ----- 个人介绍卡片 ----- */
    .intro {
      background: #ffffff;
      border-radius: 24px;
      padding: 40px 32px 32px;
      margin-bottom: 40px;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.04);
      text-align: center; /* 让内部所有内联/块级内容居中 */
    }

    .intro h1 {
      font-size: 26px;
      font-weight: 600;
      color: #1a1a1a;
      margin-bottom: 16px;
      letter-spacing: 1px;
    }

    /* 个人头像 */
    .intro-img {
      width: 30%;
      max-width: 180px;
      border-radius: 50%;  /* 圆形头像更亲切 */
      display: block;
      margin: 0 auto 24px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
      border: 2px solid #f0f0f0;
    }

    /* ★★★ 核心修改：三句话居中列表 ★★★ */
    .intro-list {
      list-style: none;      /* 去掉小黑点 */
      padding: 0;
      margin: 0 auto;
      max-width: 600px;      /* 让文字不至于太宽，提升阅读舒适度 */
    }

    .intro-list li {
      text-align: center;    /* 文字水平居中 */
      font-size: 16px;
      color: #444;
      line-height: 1.8;
      padding: 6px 0;
      border-bottom: 1px dashed rgba(0, 0, 0, 0.04); /* 轻柔分隔线，让三句话有层次 */
    }

    /* 最后一句：去掉分隔线 + 诗意味道 */
    .intro-list li:last-child {
      border-bottom: none;
      color: #7a5a3e;
      font-style: italic;
      margin-top: 4px;
    }

    /* 如果想去掉所有分隔线，直接删掉上面的 border-bottom 即可 */

    /* ----- 平台板块标题 ----- */
    .platform-title {
      text-align: center;
      font-size: 24px;
      color: #1a1a1a;
      margin: 10px 0 30px;
      font-weight: 600;
    }

    /* ----- 平台卡片网格 ----- */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 24px;
    }

    .card {
      background: #fff;
      border-radius: 20px;
      padding: 32px 24px;
      text-align: center;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.04);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 28px rgba(0, 0, 0, 0.07);
    }

    .card h3 {
      font-size: 22px;
      margin-bottom: 4px;
      color: #1a1a1a;
    }

    .fans {
      font-size: 32px;
      font-weight: 700;
      margin: 8px 0 16px;
    }

    /* 更新状态标签 */
    .status-tag {
      display: inline-block;
      font-size: 13px;
      padding: 3px 14px;
      border-radius: 30px;
      margin-bottom: 14px;
      font-weight: 500;
    }

    .update-yes {
      background: #e6f7ef;
      color: #1e8b4c;
    }

    .card-desc {
      list-style: none;
      padding: 0;
      margin: 0 0 22px;
      color: #666;
      font-size: 15px;
      line-height: 1.7;
    }

    .card-desc li {
      margin: 2px 0;
    }

    .btn {
      display: inline-block;
      padding: 10px 28px;
      border-radius: 40px;
      color: #fff;
      text-decoration: none;
      font-weight: 500;
      font-size: 15px;
      transition: opacity 0.2s, transform 0.1s;
      border: none;
      cursor: pointer;
    }

    .btn:hover {
      opacity: 0.85;
      transform: scale(0.97);
    }

    /* 知乎按钮色 */
    .btn-zhihu {
      background: #0f83fd;
    }

    /* Steam 按钮色 */
    .btn-steam {
      background: #1b2838;
    }

    /* 响应式微调 */
    @media (max-width: 600px) {
      .wrap {
        margin: 20px auto;
      }
      .intro {
        padding: 28px 18px;
      }
      .intro h1 {
        font-size: 22px;
      }
      .intro-img {
        width: 40%;
      }
      .intro-list li {
        font-size: 15px;
      }
    }
  </style>
</head>
<body>

<div class="wrap">
  <!-- 个人介绍区域 -->
  <div class="intro">
    <h1>你好，我是可爱小胖</h1>
    
    <!-- 个人配图（请将图片放置于根目录，或修改 src 路径） -->
    <img class="intro-img" src="/keaixiaopang.png" alt="可爱小胖个人头像">

    <!-- ★ 三句话完美居中展示 ★ -->
    <ul class="intro-list">
      <li>机械工程博士，高校讲师，瑞幸咖啡常客，甜甜恋爱期待者。</li>
      <li>多平台分享读博科研干货和讲师日常生活的自媒体新兵蛋子。</li>
      <li>欢迎大家关注交流，但去莫复问，白云无尽时，一起加油。</li>
    </ul>
  </div>

  <!-- 各平台板块标题 -->
  <h2 class="platform-title">📊 各平台关注者数量及运营内容</h2>

  <div class="grid">
    <!-- 知乎卡片 -->
    <div class="card">
      <span class="status-tag update-yes">持续更新</span>
      <h3>知乎</h3>
      <div class="fans" style="color:#0f83fd">5000+</div>
      <ul class="card-desc">
        <li>科研学术共勉</li>
        <li>读研读博建议</li>
        <li>日常生活分享</li>
      </ul>
      <a class="btn btn-zhihu" href="https://www.zhihu.com/people/ke-ai-xiao-pang-42" target="_blank">进入主页</a>
    </div>

    <!-- Steam 鉴赏家卡片 -->
    <div class="card">
      <span class="status-tag update-yes">持续更新</span>
      <h3>Steam 鉴赏家</h3>
      <div class="fans" style="color:#1b2838">160+</div>
      <ul class="card-desc">
        <li>游戏测评评鉴</li>
        <li>骨折游戏推荐</li>
        <li>游玩心得分享</li>
      </ul>
      <a class="btn btn-steam" href="https://steamcommunity.com/groups/keaixiaopang/curation" target="_blank">进入主页</a>
    </div>
  </div>
</div>

</body>
</html>
