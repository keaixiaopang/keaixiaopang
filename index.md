---
layout: null
---
{% comment %} 强制清空所有默认样式，彻底干掉顶线 {% endcomment %}
<style>
html, body {
  margin: 0 !important;
  padding: 0 !important;
  border: none !important;
  background: #f5f6f8;
  font-family: system-ui, -apple-system, sans-serif;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
/* 干掉可能存在的 hr、header 边框 */
hr, header, .header, .page-header {
  display: none !important;
  border: none !important;
  border-top: none !important;
  border-bottom: none !important;
}
.wrap {
  max-width: 880px;
  margin: 40px auto;
  padding: 0 20px;
}
.intro-card {
  background: #fff;
  border-radius: 18px;
  padding: 32px;
  margin-bottom: 30px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.05);
}
.intro-card h2 {
  margin: 0 0 12px;
  font-size: 22px;
  color: #222;
}
.intro-card p {
  margin: 0;
  color: #555;
  line-height: 1.7;
  font-size: 16px;
}
.platform-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px,1fr));
  gap: 20px;
}
.platform-card {
  background: #fff;
  border-radius: 18px;
  padding: 30px;
  text-align: center;
  box-shadow: 0 4px 14px rgba(0,0,0,0.05);
}
.platform-card h3 {
  margin: 0 0 12px;
  font-size: 20px;
  color: #222;
}
.fans-count {
  font-size: 28px;
  font-weight: bold;
  margin: 10px 0 22px;
}
.go-btn {
  display: inline-block;
  padding: 10px 24px;
  border-radius: 12px;
  color: #fff;
  text-decoration: none;
  font-weight: 500;
}
</style>

{% comment %} 个人介绍配置 {% endcomment %}
{% assign intro_title = "👋 关于我" %}
{% assign intro_desc = "专注无人系统、智能集群与几何优化研究，多平台分享技术干货与日常思考，欢迎各平台关注交流。" %}

{% comment %} Jekyll 原生数组：知乎 → 今日头条 → 小红书 {% endcomment %}
{% assign platforms = site.emptyArray %}
{% assign platforms = platforms | push: {name: "知乎", fans: "4000+ 人", link: "https://www.zhihu.com/people/ke-ai-xiao-pang-42", color: "#0f83fd"} %}
{% assign platforms = platforms | push: {name: "今日头条", fans: "0 人", link: "https://www.toutiao.com", color: "#ff6700"} %}
{% assign platforms = platforms | push: {name: "小红书", fans: "0 人", link: "https://www.xiaohongshu.com", color: "#ff2442"} %}

<div class="wrap">
  <div class="intro-card">
    <h2>{{ intro_title }}</h2>
    <p>{{ intro_desc }}</p>
  </div>
  <div class="platform-grid">
  {% for item in platforms %}
    <div class="platform-card">
      <h3>{{ item.name }}</h3>
      <div class="fans-count" style="color:{{ item.color }}">{{ item.fans }}</div>
      <a class="go-btn" href="{{ item.link }}" target="_blank" style="background:{{ item.color }}">进入主页</a>
    </div>
  {% endfor %}
  </div>
</div>
