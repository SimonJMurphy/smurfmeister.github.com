---
layout: default
title: Eclectic
section: Caffeine
---

Caffeine Addiction
========

It is common knowledge among my friends that I have a slight addiction to Red Bull (or equivalent energy drink). I have it under control -- only one per day, and only on work days. I enjoy it and I consider it a daily treat. You may have your own. It is an addiction that carries with it a certain stigma. I notice, however, that coffee does not have the same stigma, and I'm even shunned for <em>not</em> drinking coffee. So I took it upon myself to compare habits.

<img src="/images/caffeine_plot.png" width="600" height="300"><br>

<strong>The plot</strong><br>

The above is a plot showing the caffeine level in the body as a function of time, based on two models (explained below in 'The study'). The coffee+choc model obviously has much higher intake, but the caffeine is not completely metabolised before the next day when the 10:30 coffee is taken. This is why I had to extend the plot to cover saturday.

Just for fun, I also decided to plot the altitude of the Sun, calculated for latitude 40&deg; N (Porto -- my city of residence at the time of writing), and the current week (12-17th Nov inclusive)... Sadly, it reaches a lower altitude each day. It serves as a useful reference point for when each day starts and ends.

<strong>The study</strong><br>

I decided to study the caffeine level in the body of (a) a Red Bull addict who has, in this scenario, one can of Red Bull (or substitute) once per day. It was chosen in the scenario to combat the post-lunch dip, delivering 80mg of caffeine at 1pm. This is the same amount of caffeine as a 150ml cup of brewed coffee (though [strengths do vary somewhat](http://www.coffee.org/articles/index.php?art=182)). I call this the Red Bull model of caffeine intake. Scenario (b) is the coffee addict. My coffee addict has three cups of coffee, 150mg caffeine per cup, at 10:30, 11:00 and 14:30. My coffee addict also likes a bit of chocolate in the evenings, consuming 70mg of caffeine in the process, at 20:00. This is the coffee-choc model. 150mg caffeine per cup is a bit high, but astronomers seem to [drink more / stronger coffee](http://io9.com/5948206/here-are-the-fifteen-professions-that-drink-the-most-coffee-guess-whos-number-one) than other professions.

<strong>The mathematics</strong><br>

From a [study](http://www.ncbi.nlm.nih.gov/pubmed/11839447) of rate of absorption in caffeinated gum vs. caffeine capsules, which shows a peak caffeine level after 44.2--80.4 min for gum vs. 84.0--120.0 for capsules, I assumed that total caffeine absorption occurs after 90 minutes of ingestion (i.e. with a 100% absorption efficiency), with a linear absorption rate between the time of ingestion and the 90-minute limit. Metabolism (with half-life 4.9 hours) begins 0.1 hours after ingestion.
Caffeine intoxication - the point where a person begins to feel seriously messed up with jitters etc. - occurs at around 300 mg.

<strong>The conclusions</strong><br>

* My Red Bull habit is pretty mild.
* Perhaps some money could be made in converting this into an app, where users log their caffeine intake. Could use Starbucks as a sponsor for some advertising revenue :-)

Ironically, I did this work whilst not under the influence of Red Bull. Put it down to withdrawal symptoms.