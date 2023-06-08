<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Ronny Bergmann"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/", "Readme.md"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Julia Users Trondheim"
website_descr = "An overview on activities of Julia Users in Trondheim"
website_url   = "https://julia-users-trondheim.github,io/"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
