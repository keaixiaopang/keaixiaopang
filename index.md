---
layout: null
---

<style>
html,body{margin:0;padding:0;border:0;background:#f5f6f8;font-family:system-ui,sans-serif;}
*{margin:0;padding:0;box-sizing:border-box;}
.wrap{max-width:880px;margin:40px auto;padding:0 20px;}
.intro{background:#fff;border-radius:18px;padding:32px;margin-bottom:30px;box-shadow:0 4px 14px rgba(0,0,0,.05);}
.intro h2{margin-bottom:12px;font-size:22px;color:#222;}
.intro p{color:#555;line-height:1.7;font-size:16px;}

.intro-img {
  width: 100%;
  max-width: 400px;
  border-radius: 12px;
  margin: 20px auto 0;
  display: block;
}

.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px;}
.card{background:#fff;border-radius:18px;padding:30px;text-align:center;box-shadow:0 4px 14px rgba(0,0,0,.05);transition: all 0.3s;}
.card h3{margin-bottom:8px;font-size:20px;color:#222;}
.fans{font-size:28px;font-weight:bold;margin:10px 0 15px;}

/* 列表样式 */
.card-desc {
  list-style: none;
  padding: 0;
  margin: 0 0 20px;
  color: #666;
  font-size: 15px;
  line-height: 1.6;
}
.card-desc li {
  margin: 4px 0;
}

/* 更新状态标签 */
.status-tag {
  display: inline-block;
  font-size: 13px;
  padding: 2px 10px;
  border-radius: 20px;
  margin-bottom: 12px;
}
.update-yes {
  background: #e6f7ef;
  color: #27ae60;
}
.update-no {
  background: #f1f1f1;
  color: #999;
}

/* 停更卡片整体置灰弱化 */
.card.stop {
  background: #f9f9f9;
  opacity: 0.75;
  filter: grayscale(0.4);
}

.btn{display:inline-block;padding:10px 24px;border-radius:12px;color:#fff;text-decoration:none;font-weight:500;border:none;}
</style>

<div class="wrap">
  <div class="intro">
    <h2>👋 关于我</h2>
    <p>专注无人系统、智能集群与几何优化研究，多平台分享技术干货与日常思考，欢迎各平台关注交流。</p>
    <!-- 个人配图 自行替换文件名 -->
    <img class="intro-img" src="avatar.jpg" alt="个人配图">
  </div>

  <div class="grid">
    <!-- 知乎：持续更新 -->
    <div class="card">
      <span class="status-tag update-yes">持续更新</span>
      <h3>知乎</h3>
      <div class="fans" style="color:#0f83fd">4000+ 人</div>
      <ul class="card-desc">
        <li>无人系统研究</li>
        <li>集群协同算法</li>
        <li>学习经验分享</li>
      </ul>
      <a class="btn" href="https://www.zhihu.com/people/ke-ai-xiao-pang-42" target="_blank" style="background:#0f83fd">进入主页</a>
    </div>

    <!-- 今日头条：示例已停更 -->
    <div class="card stop">
      <span class="status-tag update-no">已暂停更新</span>
      <h3>今日头条</h3>
      <div class="fans" style="color:#ff6700">0 人</div>
      <ul class="card-desc">
        <li>科技领域解读</li>
        <li>学术干货整理</li>
        <li>日常成长记录</li>
      </ul>
      <a class="btn" href="https://www.toutiao.com" target="_blank" style="background:#ff6700">进入主页</a>
    </div>

    <!-- 小红书：示例已停更 -->
    <div class="card stop">
      <span class="status-tag update-no">已暂停更新</span>
      <h3>小红书</h3>
      <div class="fans" style="color:#ff2442">0 人</div>
      <ul class="card-desc">
        <li>学习日常打卡</li>
        <li>科研生活碎片</li>
        <li>好物与经验分享</li>
      </ul>
      <a class="btn" href="https://www.xiaohongshu.com" target="_blank" style="background:#ff2442">进入主页</a>
    </div>
  </div>
</div>
