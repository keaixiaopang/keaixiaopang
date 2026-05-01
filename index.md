---
layout: default
---

<style>
/* 彻底移除顶部头部、灰线、留白 */
.site-header {
  display: none !important;
  border-bottom: none !important;
}
.page-content {
  margin-top: 0 !important;
  padding-top: 0 !important;
  border-top: none !important;
}
body {
  border-top: none !important;
}

/* 页面布局样式 */
.container { 
  max-width: 860px; 
  margin: 40px auto; 
  padding: 0 20px; 
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; 
}
.intro { 
  background: #fff; 
  border-radius: 16px; 
  padding: 30px; 
  margin-bottom: 35px; 
  box-shadow: 0 4px 12px rgba(0,0,0,0.05); 
}
.intro h2 { 
  margin-top: 0; 
  color: #222; 
}
.intro p { 
  color: #555; 
  line-height: 1.7; 
  font-size: 16px; 
}

.grid { 
  display: grid; 
  grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); 
  gap: 20px; 
}
.card { 
  background: #fff; 
  border-radius: 16px; 
  padding: 28px; 
  box-shadow: 0 4px 14px rgba(0,0,0,0.05); 
}
.card h3 { 
  margin: 0; 
  font-size: 19px; 
  color: #222; 
}
.fans { 
  font-size: 26px; 
  font-weight: bold; 
  margin: 10px 0 20px; 
}
.btn { 
  display: block; 
  padding: 11px 18px; 
  border-radius: 10px; 
  color: #fff; 
  text-decoration: none; 
  text-align: center; 
  font-weight: 500; 
}
</style>

<div class="container">
  <div class="intro">
    <h2>{{ site.intro_title }}</h2>
    <p>{{ site.intro_content }}</p>
  </div>

  <div class="grid">
    {% for item in site.social_platforms %}
    <div class="card">
      <h3>{{ item.name }}</h3>
      <div class="fans" style="color: {{ item.color }};">{{ item.fans }} 人</div>
      <a href="{{ item.url }}" target="_blank" class="btn" style="background: {{ item.color }};">前往主页</a>
    </div>
    {% endfor %}
  </div>
</div>
