---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: page-fullwidth
header:
  #image_fullwidth: header_unsplash_12.jpg
# widget1:
#   title: "Blog & Portfolio"
#   url: 'http://phlow.github.io/feeling-responsive/blog/'
#   image: widget-1-302x182.jpg
#   text: 'Every good portfolio website has a blog with fresh news, thoughts and develop&shy;ments of your activities. <em>Feeling Responsive</em> offers you a fully functional blog with an archive page to give readers a quick overview of all your posts.'
# widget2:
#   title: "Why use this theme?"
#   url: 'http://phlow.github.io/feeling-responsive/info/'
#   text: '<em>Feeling Responsive</em> is heavily customizable.<br/>1. Language-Support :)<br/>2. Optimized for speed and it&#39;s responsive.<br/>3. Built on <a href="http://foundation.zurb.com/">Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,...'
#   video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
# widget3:
#   title: "Download Theme"
#   url: 'https://github.com/Phlow/feeling-responsive'
#   image: widget-github-303x182.jpg
#   text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. The code is well-documented and explains you how it works.'
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
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div class="row">
  <div class="columns small-12 medium-12 large-3">
    <img src="{{ site.urlimg }}group19su.jpg">
  </div>
  <div class="columns small-12 medium-12 large-6">

<section markdown="1">  
Cells are nanometer-scale problem solving machines. Our broad goal is to understand how components inside cells push, pull, bend and flow together, and how this helps cells perform tasks and exploit problem solving strategies. We use mathematical and computational modeling, in collaboration with experimentalists at UC Irvine and around the world.

We are a part of the University of California, Irvine, [Department of Mathematics](https://www.math.uci.edu/), [Department of Physics and Astronomy](https://www.physics.uci.edu/), the [Center for Complex Biological Systems](https://ccbs.uci.edu/), the [NSF-Simons Center for Multiscale Cell Fate Research](cellfate.uci.edu), and the [Chemical and Materials Physics (ChaMP)]() program at University of California Irvine.

We’re always interested in hearing from prospective graduate students and postdocs interested in modeling cell mechanics. Prospective grad students should look into our PhD program in [Mathematical, Computational and Systems Biology](https://ccbs.uci.edu/education/mcsb/).

</section>

  </div>
  <div class="columns small-12 medium-12 large-3">
    {% twitter https://twitter.com/allardlab maxwidth=500 limit=5 %}
  </div>
</div>



<!-- <div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div> -->
