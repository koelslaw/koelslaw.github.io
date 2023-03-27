---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: Screenshot 2023-03-19 171022.png
widget1:
  title: "Highlight Item 1"
  url: 'https://koelslaw.github.io/training/'
  image: widget-1-302x182.jpg
  text: 'Check out our offerings.'
widget2:
  title: "Highlight Item 2"
  image: marvin-meyer-SYTO3xs06fU-unsplash-smaller.jpg
  url: 'https://koelslaw.github.io/consulting/'
  text: 'Want custom consulting around a solution? See what we can offer!'
widget3:
  title: "Highlight Item 3"
  image: marvin-meyer-SYTO3xs06fU-unsplash-smaller.jpg
  url: 'https://koelslaw.github.io/team/'
  text: 'Meet the members of the team'

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
  url: https://koelslaw.github.io/contact/
  text: Start a Conversation ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<!-- <div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div> -->
