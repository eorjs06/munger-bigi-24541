---
title: "찰리 멍거 선생님의 비기 제 24541장"
---

> 잠자리에 들 때는 아침에 일어났을 때보다 조금 더 현명해져 있어라. — 찰리 멍거 (의역)

매일 경제 뉴스 3가지, 용어 1개, 생각의 도구 1개.

📖 **[나의 경제 용어장](glossary.html)**: 지금까지 배운 용어 모음

## 📰 브리핑 목록

{% assign items = site.pages | where_exp: "p", "p.path contains 'briefings/'" | sort: "date" | reverse %}
{% for p in items %}
- **[{{ p.date | date: "%Y-%m-%d" }}]({{ p.url | relative_url }})** · {{ p.summary }}
{% endfor %}
