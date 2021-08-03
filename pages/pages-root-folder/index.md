---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg

widget1:
  title: "Flav Creations"
  url: '/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: "Welcome to Flav Creations. Flavius is an Indie Dev that creates games, apps, websites and various tools. Here on FlavCreations.com I will be posting blogs about my game development alongside posting information about games, tools, and websites I'm working on."
#
widget2:
  title: "Github Projects"
  url: 'https://github.com/Flavius-The-Person?tab=repositories'
  image: widget-github-303x182.jpg
  text: "I've been working on my own projects, some open source, some not. At one time I even made my own engine of sorts in Java called the Stream Warriors Engine. It was even almost ready to put out into the wild until I decided it would be better to use a proper framework or engine for game development. I have been learning Monogame/XNA with C# since."


#widget3:
#  title: "Download Theme"
#  url: 'https://github.com/Phlow/feeling-responsive'
#  image: widget-github-303x182.jpg
#  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. The code is well-documented and explains you how it works.'
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
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
