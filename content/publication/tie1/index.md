---
# (1) 文章名
title: "OM2S2: On-Line Moisture-Sensing System Using Multifrequency Microwave Signals Optimized by a Two-Stage Frequency Selection Framework"

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

# (4) 我写的是论文接收时间 October 12, 2020
date: "2020-10-12T00:00:00Z"
doi: "10.1109/TIE.2020.3032927"

# (5) 不清楚这个时间，是显示到哪里，目前貌似也没见到过这个
# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-27T00:00:00Z"


# (6) 出版物类型，注意这里可选择为 Patent
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
publication: In *IEEE Transactions on Industrial Electronics*
publication_short: In *IEEE TIE*

# (8) 摘要
abstract: In this article, an on-line microwave moisture sensing system (OM2S2) based on a multifrequency swept technique was developed to monitor the moisture content (MC) of corn in the fresh to dry state (MC ranged from 10.89% to 63.64%) in real time. Attenuation and phase shift data were collected under a frequency swept signal containing 801 frequencies from 2.00 to 10.00 GHz with a 10 MHz interval. To remove the inefficient frequencies, the optimized frequencies were selected by a two-stage frequency selection framework: (1) 17 frequency subsets were generated using the random forest-recursive feature elimination algorithm, and then (2) the optimal frequency set (including eight individual frequencies) was determined using voting strategies according to the results of ten-fold cross-validation. The attenuation and phase shift data corresponding to the optimal frequency set were utilized as the input variables of six regression algorithms for MC prediction. A deep neural network [coefficient of determination (R2) = 0.997, root mean square error (RMSE) = 1.087, mean absolute error (MAE) = 0.868] performed best according to the Friedman test and Nemenyi post hoc test and thus, was employed for the OM2S2. These results showed that the OM2S2 could measure the MC of corn changing from the fresh state to the dry state in real time, and it showed potential for utilization in the on-line determination of high MC in food processing and agriculture-related industries.

# (9) 如果设置为 "Featured Publications"，那么这个summary会显示到图片下方，否则就不会显示出来！
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [paper]

# (10) “开关”，控制是否显示到 "Featured"部件中，即是否为特色文章，或代表作
# Display this page in the Featured widget?
featured: true

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
projects:
- example

# (13) 觉得没必要，所以注释掉
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example


---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).





