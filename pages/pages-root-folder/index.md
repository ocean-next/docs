---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "mer_orig_montage_curl.jpg"
widget1:
  title: "Who we are"
  url: /team/
  image: earth20161122_800x800.jpg
  text: 'We are a team of scientists contributing to fundamental and applied research projects on the oceans and inland waters. [...]'
widget2:
  title: "What we do"
  url: /expertise/
  image: eNATL60_zoom_800x800.jpg
  text: 'We produce, collect and interpret geoscientific data in relation to the ocean and inland waters. [...]'
widget3:
  title: "Our story"
  url: /about-us/
  image: manchots_800x800.jpg
  text: 'Our company Ocean Next was founded in 2017 on the initiative of Jacques Verron, oceanographer and expert in data assimilation for  operational oceanography. [...]'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /contact/
  text: Contact us ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
