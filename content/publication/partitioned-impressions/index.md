---
title: "Sustaining a Good Impression: Mechanisms for Selling 'Partitioned' Impressions at Ad-Exchanges"
authors:
- admin
- Milind Dawande
- Ganesh Janakiraman
- Vijay Mookerjee

date: "2019-05-18"
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Information Systems Research* (forthcoming)"
publication_short: ""

abstract: "In the mobile advertising ecosystem, the role of ad-exchanges to match advertisers and publishers has grown significantly over the past few years. At a mobile ad-exchange, impressions (i.e., opportunities to display ads) are sold to advertisers in real time through an auction mechanism. The traditional mechanism selects a single advertiser whose ad is displayed over the entire duration of an impression, i.e., throughout the user's visit. We argue that such a mechanism leads to an allocative inefficiency, as displaying only the winning ad throughout the lifetime of an impression precludes the exchange from exploiting the opportunity to obtain additional revenue from advertisers whose willingness-to-pay becomes higher during the lifetime of that impression. Our goal in this paper is to address this efficiency loss by offering mechanisms in which multiple ads can be displayed sequentially over the lifetime of the impression. We consider two plausible settings – one, where each auction is individually rational for the advertisers and the other, where advertisers are better off relative to the traditional mechanism over the long run – and derive an optimal (i.e., revenue-maximizing for the ad-exchange) mechanism for each setting. To efficiently compute the payment rule, the optimal mechanism for the former setting uses randomized payments. Under this mechanism, while the ad-exchange always benefits relative to the traditional mechanism, the advertisers could either gain or lose – we demonstrate both these possibilities. The optimal mechanism for the latter setting is a 'mutually-beneficial' mechanism in that it guarantees a win-win for both the parties relative to the traditional mechanism, over the long run. Happily, for both the mechanisms, the allocation of ads and the payments from the advertisers are efficiently computable, thereby making them amenable to real-time bidding."

# Summary. An optional shortened abstract.
summary: We obtain optimal mechanisms for ad-exchanges in which multiple ads can be displayed sequentially over the lifetime of an impression.

tags:
- Mobile Advertising
- Ad-Exchanges
- Optimal Mechanisms
- Mutually-Beneficial Mechanisms
featured: false

links:
 - name: "SSRN"
   url: "https://ssrn.com/abstract=3064299"
url_pdf: 'PartitionedImpressions.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---


