---
layout: post
title: Strava Analysis - Identifying Injury Risk
---

Over the last three years I have trained fairly consistently as a long to ultra distance runner. Although I'm no esteemed athlete, recreational running has offered me a great deal of purpose and achievement. I've completed Ultra Trail Australia 50km & 100km, ANU's Inward Bound Division 1, circumnativagated Mont Blanc and competed in various local events. Injury plagues the recreational runner as much as a well seasoned athlete. There is a fine and highly variable balance to be achieved by training regime that optimises fitness without breaking the body. 

<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>

I was interested in quantifying the accumulated intensity of my training, applying a decay function to model recovery time, and comparing the smoothed intensity data to recorded injuries and personal bests. For a quick preview, the red bars gives the accumulated training intensity on the date of an activity, the blue shows where personal bests were achieved, and the green shows in injuries. Whilst the model was able to recognise my injury in Sept 2019, distinctly caused by overloading, the other more acute injuries were less predictable.


({{ site.baseurl }}/images/running.png)

Find my whole analysis and rationale here: 

<a href="https://apahljina.github.io/Applied-Statistical-Analytics---Distance-Running.html" title="Distance Running Analysis in R">Distance Running Analysis in R</a>


