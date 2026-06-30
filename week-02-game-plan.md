
```mermaid
mindmap
root ((Pac-Man))
	Theme
	 เขาวงกต
	 อาเขตยุค 80
	Mechanics
	เดินในเขาวงกต
	 กิน Pellet
	Power Pellet
	Content
	 ผีศัตรู 4 ตัว
	 ผลไม้โบนัส
	Audience
	 ผู้เล่น Casual
	artstyle
	 pixel art
	 stylized
```


```mermaid
quadrantChart
title Pac-Man — Feature Prioritization
x-axis Low Effort --> High Effort
y-axis Low Impact --> High Impact
quadrant-1  Quick Wins
quadrant-2  Major
quadrant-3  Nice to Have
quadrant-4  Reconsider
Maze Movement: [0.3, 0.95]
Ghost AI: [0.7, 0.9]
Online Leaderboard: [0.7, 0.3]
score & pallate system : [0.2 , 0.85]
Power pellets : [0.4 , 0.9]
sound effect & music : [0.3 , 0.7]
skin & cosmetic : [0.6 , 0.2]
```



```mermaid
gantt
title Pac-Man — Production Timeline (6 สัปดาห์)
dateFormat YYYY-MM-DD
section Pre-Production
Concept & GDD :done, c1, 2026-07-06, 5d
section Production
Maze Movement :active, p1, after c1, 5d
Ghost AI : p2, after p1, 7d
Pellet & Score : p3, after p2, 7d
section Post
QA & Bug Fix : q1, after p3, 5d
Release Build :milestone, m1, after q1, 0d
sound effect & UI : p4 , after p1 , 6d
beta version : milestone , m0 , after p3 ,0d

```




<style>#mermaid-1782809274564{font-family:sans-serif;font-size:16px;fill:#333;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1782809274564 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1782809274564 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1782809274564 .error-icon{fill:#552222;}#mermaid-1782809274564 .error-text{fill:#552222;stroke:#552222;}#mermaid-1782809274564 .edge-thickness-normal{stroke-width:1px;}#mermaid-1782809274564 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1782809274564 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1782809274564 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1782809274564 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1782809274564 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1782809274564 .marker{fill:#333333;stroke:#333333;}#mermaid-1782809274564 .marker.cross{stroke:#333333;}#mermaid-1782809274564 svg{font-family:sans-serif;font-size:16px;}#mermaid-1782809274564 p{margin:0;}#mermaid-1782809274564 .node .neo-node{stroke:#9370DB;}#mermaid-1782809274564 [data-look="neo"].node rect,#mermaid-1782809274564 [data-look="neo"].cluster rect,#mermaid-1782809274564 [data-look="neo"].node polygon{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809274564 [data-look="neo"].node path{stroke:#9370DB;stroke-width:1px;}#mermaid-1782809274564 [data-look="neo"].node .outer-path{filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809274564 [data-look="neo"].node .neo-line path{stroke:#9370DB;filter:none;}#mermaid-1782809274564 [data-look="neo"].node circle{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809274564 [data-look="neo"].node circle .state-start{fill:#000000;}#mermaid-1782809274564 [data-look="neo"].icon-shape .icon{fill:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809274564 [data-look="neo"].icon-shape .icon-neo path{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809274564 :root{--mermaid-font-family:sans-serif;}#mermaid-1782809274564 :root{--mermaid-alt-font-family:sans-serif;}</style>



<style>#mermaid-1782809547997{font-family:sans-serif;font-size:16px;fill:#333;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1782809547997 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1782809547997 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1782809547997 .error-icon{fill:#552222;}#mermaid-1782809547997 .error-text{fill:#552222;stroke:#552222;}#mermaid-1782809547997 .edge-thickness-normal{stroke-width:1px;}#mermaid-1782809547997 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1782809547997 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1782809547997 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1782809547997 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1782809547997 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1782809547997 .marker{fill:#333333;stroke:#333333;}#mermaid-1782809547997 .marker.cross{stroke:#333333;}#mermaid-1782809547997 svg{font-family:sans-serif;font-size:16px;}#mermaid-1782809547997 p{margin:0;}#mermaid-1782809547997 .node .neo-node{stroke:#9370DB;}#mermaid-1782809547997 [data-look="neo"].node rect,#mermaid-1782809547997 [data-look="neo"].cluster rect,#mermaid-1782809547997 [data-look="neo"].node polygon{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809547997 [data-look="neo"].node path{stroke:#9370DB;stroke-width:1px;}#mermaid-1782809547997 [data-look="neo"].node .outer-path{filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809547997 [data-look="neo"].node .neo-line path{stroke:#9370DB;filter:none;}#mermaid-1782809547997 [data-look="neo"].node circle{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809547997 [data-look="neo"].node circle .state-start{fill:#000000;}#mermaid-1782809547997 [data-look="neo"].icon-shape .icon{fill:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809547997 [data-look="neo"].icon-shape .icon-neo path{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809547997 :root{--mermaid-font-family:sans-serif;}#mermaid-1782809547997 :root{--mermaid-alt-font-family:sans-serif;}</style>


<style>#mermaid-1782809680822{font-family:sans-serif;font-size:16px;fill:#333;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1782809680822 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1782809680822 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1782809680822 .error-icon{fill:#552222;}#mermaid-1782809680822 .error-text{fill:#552222;stroke:#552222;}#mermaid-1782809680822 .edge-thickness-normal{stroke-width:1px;}#mermaid-1782809680822 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1782809680822 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1782809680822 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1782809680822 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1782809680822 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1782809680822 .marker{fill:#333333;stroke:#333333;}#mermaid-1782809680822 .marker.cross{stroke:#333333;}#mermaid-1782809680822 svg{font-family:sans-serif;font-size:16px;}#mermaid-1782809680822 p{margin:0;}#mermaid-1782809680822 .node .neo-node{stroke:#9370DB;}#mermaid-1782809680822 [data-look="neo"].node rect,#mermaid-1782809680822 [data-look="neo"].cluster rect,#mermaid-1782809680822 [data-look="neo"].node polygon{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809680822 [data-look="neo"].node path{stroke:#9370DB;stroke-width:1px;}#mermaid-1782809680822 [data-look="neo"].node .outer-path{filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809680822 [data-look="neo"].node .neo-line path{stroke:#9370DB;filter:none;}#mermaid-1782809680822 [data-look="neo"].node circle{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809680822 [data-look="neo"].node circle .state-start{fill:#000000;}#mermaid-1782809680822 [data-look="neo"].icon-shape .icon{fill:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809680822 [data-look="neo"].icon-shape .icon-neo path{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809680822 :root{--mermaid-font-family:sans-serif;}#mermaid-1782809680822 :root{--mermaid-alt-font-family:sans-serif;}</style>


<style>#mermaid-1782809151835{font-family:sans-serif;font-size:16px;fill:#333;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1782809151835 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1782809151835 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1782809151835 .error-icon{fill:#552222;}#mermaid-1782809151835 .error-text{fill:#552222;stroke:#552222;}#mermaid-1782809151835 .edge-thickness-normal{stroke-width:1px;}#mermaid-1782809151835 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1782809151835 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1782809151835 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1782809151835 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1782809151835 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1782809151835 .marker{fill:#333333;stroke:#333333;}#mermaid-1782809151835 .marker.cross{stroke:#333333;}#mermaid-1782809151835 svg{font-family:sans-serif;font-size:16px;}#mermaid-1782809151835 p{margin:0;}#mermaid-1782809151835 .node .neo-node{stroke:#9370DB;}#mermaid-1782809151835 [data-look="neo"].node rect,#mermaid-1782809151835 [data-look="neo"].cluster rect,#mermaid-1782809151835 [data-look="neo"].node polygon{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809151835 [data-look="neo"].node path{stroke:#9370DB;stroke-width:1px;}#mermaid-1782809151835 [data-look="neo"].node .outer-path{filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809151835 [data-look="neo"].node .neo-line path{stroke:#9370DB;filter:none;}#mermaid-1782809151835 [data-look="neo"].node circle{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809151835 [data-look="neo"].node circle .state-start{fill:#000000;}#mermaid-1782809151835 [data-look="neo"].icon-shape .icon{fill:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809151835 [data-look="neo"].icon-shape .icon-neo path{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809151835 :root{--mermaid-font-family:sans-serif;}#mermaid-1782809151835 :root{--mermaid-alt-font-family:sans-serif;}</style>


<style>#mermaid-1782809258258{font-family:sans-serif;font-size:16px;fill:#333;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1782809258258 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1782809258258 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1782809258258 .error-icon{fill:#552222;}#mermaid-1782809258258 .error-text{fill:#552222;stroke:#552222;}#mermaid-1782809258258 .edge-thickness-normal{stroke-width:1px;}#mermaid-1782809258258 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1782809258258 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1782809258258 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1782809258258 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1782809258258 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1782809258258 .marker{fill:#333333;stroke:#333333;}#mermaid-1782809258258 .marker.cross{stroke:#333333;}#mermaid-1782809258258 svg{font-family:sans-serif;font-size:16px;}#mermaid-1782809258258 p{margin:0;}#mermaid-1782809258258 .node .neo-node{stroke:#9370DB;}#mermaid-1782809258258 [data-look="neo"].node rect,#mermaid-1782809258258 [data-look="neo"].cluster rect,#mermaid-1782809258258 [data-look="neo"].node polygon{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809258258 [data-look="neo"].node path{stroke:#9370DB;stroke-width:1px;}#mermaid-1782809258258 [data-look="neo"].node .outer-path{filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809258258 [data-look="neo"].node .neo-line path{stroke:#9370DB;filter:none;}#mermaid-1782809258258 [data-look="neo"].node circle{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809258258 [data-look="neo"].node circle .state-start{fill:#000000;}#mermaid-1782809258258 [data-look="neo"].icon-shape .icon{fill:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809258258 [data-look="neo"].icon-shape .icon-neo path{stroke:#9370DB;filter:drop-shadow(1px 2px 2px rgba(185, 185, 185, 1));}#mermaid-1782809258258 :root{--mermaid-font-family:sans-serif;}#mermaid-1782809258258 :root{--mermaid-alt-font-family:sans-serif;}</style>
