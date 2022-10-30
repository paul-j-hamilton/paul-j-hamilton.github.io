---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## CASES AND TEACHING MATERIALS

---

Bojinov, Iavor I., Michael Parzen, and Paul Hamilton. "Prediction & Machine Learning." Harvard Business School Module Note 622-101, March 2022. (Revised July 2022.) https://www.hbs.edu/faculty/Pages/item.aspx?num=62273. 

Bojinov, Iavor, Michael Parzen, and Paul Hamilton. "Causal Inference." Harvard Business School Module Note 622-111, June 2022. (Revised July 2022.) https://www.hbs.edu/faculty/Pages/item.aspx?num=62522.

Bojinov, Iavor I., Michael Parzen, and Paul Hamilton. "Linear Regression." Harvard Business School Module Note 622-100, March 2022. (Revised July 2022.) https://www.hbs.edu/faculty/Pages/item.aspx?num=62264. 

Bojinov, Iavor I., Michael Parzen, and Paul Hamilton. "Statistical Inference." Harvard Business School Module Note 622-099, March 2022. (Revised July 2022.) https://www.hbs.edu/faculty/Pages/item.aspx?num=62263. 

Bojinov, Iavor I., Michael Parzen, and Paul Hamilton. "Exploratory Data Analysis." Harvard Business School Module Note 622-098, March 2022. (Revised July 2022.) https://www.hbs.edu/faculty/Pages/item.aspx?num=62261.

Parzen, Michael, and Paul Hamilton. "Probability Distributions." Harvard Business School Technical Note 621-704, February 2021. https://www.hbs.edu/faculty/Pages/item.aspx?num=59337.

Bojinov, Iavor I., Chiara Farronato, Janice H. Hammond, Michael Parzen, and Paul Hamilton. "Precision Paint Co." Harvard Business School Case 622-055, August 2021. https://www.hbs.edu/faculty/Pages/item.aspx?num=61106.

Datar, Srikant M., Amram Migdal, and Paul Hamilton. "IBM: Design Thinking." Harvard Business School Case 121-007, April 2021. (Revised June 2021.) https://www.hbs.edu/faculty/Pages/item.aspx?num=60141.

Parzen, Michael, and Paul Hamilton. "The FIRE Savings Calculator." Harvard Business School Case 621-087, January 2021. https://www.hbs.edu/faculty/Pages/item.aspx?num=59370.

Datar, Srikant M., Sarah Mehta, and Paul Hamilton. "Applying Data Science and Analytics at P&G." Harvard Business School Case 121-006, July 2020. https://www.hbs.edu/faculty/Pages/item.aspx?num=58380.

Grushka-Cockayne, Yael, Michael Parzen, Paul Hamilton, and Steven Randazzo. "Kaggle 2019 Data Science Survey." Harvard Business School Case 620-091, January 2020. https://www.hbs.edu/faculty/Pages/item.aspx?num=57488.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
