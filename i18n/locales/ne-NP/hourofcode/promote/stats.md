* * *

title: <%= hoc_s(:title_stats) %> layout: wide nav: promote_nav

* * *

<%= view :signup_button %>

# Blurbs and Useful Stats

## Use this short blurb in newsletters

### Bring computer science to your school. Start with an Hour of Code

कम्प्युटरहरू जहाँ तहिँ हुन्छन्, तर केहि विद्यालयहरूले मात्र 10 वर्ष अघि देखि कम्प्युटर विज्ञान पढाई राखेका छन्। राम्रो खबर हो, हामीले हाम्रो बाटोबाट यसलाई परिवर्तन गरि राखेका छौँ। If you heard about the [Hour of Code](%= resolve_url('/') %) last year, you might know it made history. In the first Hour of Code, 15 million students tried computer science. Last year, that number increased to 60 million students! The [Hour of Code](%= resolve_url('/') %) is a one-hour introduction to computer science, designed to demystify code and show that anybody can learn the basics. [Sign up](%= resolve_url('/') %) to host an Hour of Code this <%= campaign_date('full') %> during Computer Science Education Week. To add your school to the map, go to https://hourofcode.com/<%= @country %>

## Infographics

<%= view :stats_carousel %>

<%= view :signup_button %>