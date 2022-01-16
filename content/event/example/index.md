---
# (1) 报告题目
title: "Determination of Moisture Content of Sweet Corn by Using Multifrequency Microwaves Swept Measurement"

# (2) 会议信息
event: Chinese Society for Agricultural Machinery (CSAM) Academic Annual Conference 2018
event_url: http://www.agro-csam.org/english/index.shtml

# (3) 地址
location: Anxiang Relax Hotel
address:
  street: 1618 Jincheng Rd
  city: Hangzhou
  region: ZJ
  postcode: '310030'
  country: China

# (4) 显示在主页，报告题目下的一句小总结，我是换成了大会名称
summary: CSAM 2018 Academic Annual Conference.

# (5) 摘要
abstract: Moisture measurement has long been a challenge for agricultural products with high moisture content (MC). In view of this, our team built a novel microwave sensing system with off-the-shelf components and applied the system to moisture determination of sweet corn (MC is approximately 80% w.b.). To collect sufficient moisture information, a frequency-swept signal (contains 41 frequencies from 2.60 to 3.00 GHz) was taken as the original measurement signal. A total of 20 redundant frequencies were removed from the original measurement signal according to the frequency selection for further measurements. Four different algorithms, including deep neural network (DNN), random forest (RF), adaptive boosting (AdaBoost), and extreme gradient boosting (XGBoost), were employed to establish moisture prediction models. The proposed six-layer DNN showed the best performance (R<sup>2</sup> = 0.980, RMSE = 2.023%, and MAE = 1.556%) in predicting the MC of sweet corn (ranging from 15.45% to 81.19% w.b.). The results showed that the developed microwave sensing system was capable of measuring the MC of sweet corn, and the system could potentially be applied to moisture determination of other agricultural products with high MC in the food processing industry.

# (6) 汇报时间，参考网页：http://www.agro-csam.org/xhhd/gjjl/zyxw/2018/11/65886.shtml
# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2018-11-25T10:00:00Z"
date_end: "2018-11-25T11:00:00Z"
all_day: false

# (7) 与Publications和Patents一样，我还是不清楚这个"publishDate"到底是显示到哪里？
# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

# (8) 在主页，汇报日期下方，显示汇报人；在点击题目后，页面最下方，显示标签
authors: [admin]
tags: [Oral Presentations]

# (9) “开关”，控制是否显示到 "Featured"部件中，即是否为特色文章，或代表作
# Is this a featured talk? (true/false)
featured: false

# (10) 图片
image:
  caption: 'Image credit: [**CSAM**](http://www.agro-csam.org/english/index.shtml)'
  focal_point: Right

# (11) 左上方标签
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# (12) 幻灯片(觉得没必要，可以注释掉)
# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# (13) 相关的项目
# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.
