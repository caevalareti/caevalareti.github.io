---
title: What data can tell about your coffee?
excerpt: >-
  Everybody loves coffee. But here is the question, which country has the best coffee beans in the world?
date: 2020-05-09
thumb_img_path: images/coffee1.jpg
content_img_path: images/coffee1.jpg
layout: post
---

Photo by [Mike Keneally](https://images.unsplash.com/photo-1497515114629-f71d768fd07c?ixlib=rb-1.2.1&auto=format&fit=crop&w=1362&q=80)

For millions of people around the globe, coffee is an essential morning ritual that fuels the start of their day and most of the time, you don't realize it. But behind every sip of coffee, there's a fascinating story that begins in the country where it was cultivated and end with the choice of cup that carries it your lips.

The analysis here presented will provide an array of helpful insights of the bests coffee types in the world. Where it comes from, how people make and consume it, and things to consider when choose the best type for your profile.

The dataset is from [The Coffee Quality Institute](https://www.coffeeinstitute.org/), a non-profit organization that grades coffee from all over the world. It contains the grades that cuppers gave to attributes like: Flavor, Aftertaste, Aroma, Acidity, Balance, Uniformity, and more. If you want to get the explanation about what exactly each attribute is you can check [The Coffee Database](https://database.coffeeinstitute.org/).

#### Let's introduce the types of coffee

In supermarkets you’ll probably find to types of coffee beans for sale: Arabica and Robusta. You may ask yourself about the difference between them, so here it comes.

**Arabica** is the most popular type of coffee. Typically used for black coffee, Arabica beans have a sweeter, more complex flavor that you can drink straight. Funny thing is, even though it’s popular, it doesn’t have as much caffeine as Robusta.

<img src="https://www.nicepng.com/png/full/254-2541870_types-of-coffee-beans-arabica-coffee-bean.png" width=720 height=480>

[Differences between the beans.](https://www.nicepng.com/png/full/254-2541870_types-of-coffee-beans-arabica-coffee-bean.png)

**Robusta** is cheaper and stronger. Because of its bitter flavor, you’ll typically see Robusta used for espresso drinks and in instant coffee mixes. If you are feeling lazy, reach for a cup of coffee that uses Robusta beans. High cafeine will wake you right up!

Now that you know the differences between coffee beans, we can start for the data analysis. First we're going to talk about the Arabica bean. The dataset records each coffee sample's country of origin and with this we can build a coffee profile for each nation. All the results were pretty close, to mention this further, the median score on various atributes like uniformity, sweetness and clean cup was perfect for most of them.

#### Highest Ranked Country

<div class="responsive-table">
  <table>
    <caption>Arabica coffee rank</caption>
    <thead>
      <tr>
        <th>Attribute</th>
        <th>Country</th>
        <th>Score</th>   
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Aroma</td>
        <td>Papua New Guine</td>
        <td>8.330</td>
      </tr>
      <tr>
        <td>Flavor</td>
        <td>Papua New Guine</td>
        <td>8.420</td>
      </tr>
      <tr>
        <td>Aftertaste</td>
        <td>United States of America</td>
        <td>8.125</td>
      </tr>
      <tr>
        <td>Acidity</td>
        <td>Papua New Guine</td>
        <td>8.330</td>
      </tr>
      <tr>
        <td>Body</td>
        <td>Japan</td>
        <td>8.080</td>
      </tr>
      <tr>
        <td>Balance</td>
        <td>Papua New Guine</td>
        <td>8.250</td>
      </tr>
      <tr>
        <td>Cupper points</td>
        <td>United States of America</td>
        <td>8.170</td>
      </tr>
      <tr>
        <td>Total Cup Points</td>
        <td>United States of America</td>
        <td>87.125</td>
      </tr>
    </tbody>
  </table>
</div>

Uniformity, clean cup and sweetness were not mentioned because all countries scored 10.
We can see that USA ranks the highest in 6 out of 10 areas of grading. And data tell us that the best coffee of the world is from Hawaii, USA.

<img src="https://raw.githubusercontent.com/caevalareti/caevalareti.github.io/master/static/images/coffee-hawaii.png">

[AKA Chart available here.](https://raw.githubusercontent.com/caevalareti/caevalareti.github.io/master/static/images/coffee-hawaii.png)

Robusta dataset was not so large as Arabica one. We made an observation with only 28 samples, compared to Arabica which was 1311 samples, is just a few. But here comes our analysis.

<div class="responsive-table">
  <table>
    <caption>Robusta coffee rank</caption>
    <thead>
      <tr>
        <th>Attribute</th>
        <th>Country</th>
        <th>Score</th>   
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Fragrance and Aroma</td>
        <td>Uganda</td>
        <td>7.830</td>
      </tr>
      <tr>
        <td>Flavor</td>
        <td>Uganda</td>
        <td>7.790</td>
      </tr>
      <tr>
        <td>Salt and Acidity</td>
        <td>India</td>
        <td>7.830</td>
      </tr>
      <tr>
        <td>Bitter and Sweet</td>
        <td>Ecuator</td>
        <td>8.085</td>
      </tr>
      <tr>
        <td>Mouthfeel</td>
        <td>India</td>
        <td>7.750</td>
      </tr>
      <tr>
        <td>Balance</td>
        <td>India</td>
        <td>7.750</td>
      </tr>
      <tr>        
        <td>Total Cup Points</td>
        <td>Uganda</td>
        <td>81.625</td>
      </tr>
    </tbody>
  </table>
</div>

<img src="https://raw.githubusercontent.com/caevalareti/caevalareti.github.io/master/static/images/robusta-india.png">

[AKA Chart available here.](https://raw.githubusercontent.com/caevalareti/caevalareti.github.io/master/static/images/robusta-india.png)

Although the Total cup points shows Uganda in the first place, a sample of Robusta from India has the best characteristics among the other data analyzed.

You can find the code used to build this review in my [GitHub repo](https://bit.ly/2WiHhEh). Feel free to check it out or get in touch.

Thanks for reading.
