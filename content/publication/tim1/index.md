---
# (1) 题目
title: "Development of Multifrequency-Swept Microwave Sensing System for Moisture Measurement of Sweet Corn with Deep Neural Network"

# (2) 作者 Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jun Wang
- Zhenbo Wei

# (3) 作者备注信息
# Author notes (optional)
author_notes:
- "The First Author"
- ""
- "Corresponding Author"

# (4) 出版信息
date: "2020-02-12T00:00:00Z"
doi: "10.1109/TIM.2020.2972655"

# (5) 不清楚这个时间，是显示到哪里，目前貌似也没见到过这个
# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-27T00:00:00Z"

# (add) 左上方标签
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/tylerzhang09

# (6) 出版物类型
# Publication type.
# Legend: 
# 0 = Uncategorized; 
# 1 = Conference paper; 
# 2 = Journal article;
# 3 = Preprint / Working Paper; 
# 4 = Report; 
# 5 = Book; 
# 6 = Book section;
# 7 = Thesis; 
# 8 = Patent
publication_types: ["2"]

# (7) 期刊名称 缩写
# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Instrumentation and Measurement*
publication_short: In *IEEE Transactions on Instrumentation and Measurement*

# (8) 摘要
# Abstract
abstract: Moisture measurement has long been a challenge for agricultural products with high moisture content (MC). In this article, a novel microwave sensing system embedded with multifrequency-swept technique was built with off-the-shelf components and applied to moisture measurement of sweet corn [MC is approximately 80% wet basis (w.b.)]. In order to collect sufficient moisture information, a frequency-swept signal (contains 41 frequencies from 2.60 to 3.00 GHz) was taken as the original measurement signal. A total of 20 redundant frequencies were removed from the original measurement signal according to the frequency selection for further measurements. Four different algorithms, including deep neural network (DNN), random forest (RF), adaptive boosting (AdaBoost), and extreme gradient boosting (XGBoost), were employed to establish moisture prediction models. The proposed six-layer DNN showed the best performance (R<sup>2</sup> = 0.980, RMSE = 2.023%, and MAE = 1.556%) in predicting the MC of sweet corn (ranging from 15.45% to 81.19% w.b.). The results showed that the developed microwave sensing system was capable of measuring the MC of sweet corn and could potentially be applied to moisture determination of other agricultural products with high MC in food processing industry.

# (9) 如果设置为 "Featured Publications"，那么这个summary会显示到图片下方，否则就不会显示出来！
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [paper]

# (10) “开关”，控制是否设置为 "Featured Publications"
# Display this page in the Featured widget?  (Very Very Very important!!!)
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# (11) 图片
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**IEEE Xplore**](https://ieeexplore.ieee.org/Xplore/home.jsp)'
  focal_point: ""
  preview_only: false

# (12) 相关的项目
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# (13) 觉得没必要，所以注释掉
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example



#{{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}

#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).


---

