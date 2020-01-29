---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Estimating Multivariate Stochastic Volatility Models with Particle MCMC"
event: "Tom Tom Applied Machine Learning Conference"
event_url: "https://tomtomfest.com/machine-learning/machine-learning-sessions/"
location:
summary: 
abstract: "Factor Stochastic Volatility (FSV) models are useful for managing investment risk and constructing portfolios. They possess a latent low-dimensional random process to help explain a higher-dimensional vector of finacial returns. This hidden process can represent anything the investor deems pertinent
Despite being expressive models in this class are exceedingly difficult to estimate. Within a Bayesian framework Gibbs sampling is the most common approach yet this is only available for some models used along with certain priors. Variants of Metropolis-Hastings are theoretically justified however they do not mix well in practice.
We argue that Particle Markov chain Monte Carlo techniques a newer set of likehood-free MCMC algorithms are well-suited to this task. We describe the general principles of the algorithm strategies for parallelization and show some examples of estimating different models. We also demonstrate once these models are estimated their out-of-sample forecasting performance. "

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-04-11
#date_end: 2019-04-11T17:27:15-04:00
#all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: 2019-06-11T17:27:15-04:00

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: "http://people.virginia.edu/~trb5me/taylors_tomtom_pres.pdf"

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
