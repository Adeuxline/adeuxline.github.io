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
  title: "Monnaies locales"
  url: 'http://adeuxline.github.io/blog/'
  image: http://www.levif.be/medias/6982/3574825.jpg
  text: 'Le premier objectif de ce voyage est de faire un tour du monde des monnaies alternatives.'
widget2:
  title: "Pourquoi le stop ?"
  url: '#'
  text: 'Le stop est un moyen gratuit de voyager et de faire de merveilleuses rencontres.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Challenges des enfants"
  url: '#'
  image: widget-github-303x182.jpg
  text: 'Un des objectifs de ce voyage est de faire voyager et rêver les enfants hospitalisés.'
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
  url: https://tinyletter.com/feeling-responsive
  text: S'abonner à la newsletter (qui n'existe pas encore) ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

{% include google_maps_settings.html %}
{% include google_maps.html %}
{% include google_maps_markers.html %}
{% include google_maps_end.html %}
