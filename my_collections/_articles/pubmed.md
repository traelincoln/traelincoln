---
title: Links to some interesting research papers
permalink: /blog/research-papers
layout: default

links:
  - title: All the single ladies put your hands up!
  summary: South Afican men are getting married on average at 37 years old and women on average at 33 years old. Most never married men marry never married women in south africa, and most men marry younger women most women marry older women. On average South African men get devorced at 45 years old and women at 41 years old.
  source: www.statssa.gov.za/?p=14113
  author: unspecified 
  summary-type: article

  - title: Gender differences in mate selection criteria among university students in Bangladesh: A study from the social homogamy perspective 
  author: Md Nurul Islam
  summary: Men and women have different preferences when choosing potential marriage partners and these differences vary with culture. For most cultures both sexes prefer to marry partners who are closer to them in age, have similar social backgrounds to their own, as well as religious beliefs and sometimes level of education. Like pairs with like. Men strongly value youth and physical attractiveness across many cultures.  Women consider more traits in their partners including but not limited to financial prospects, intelligence and level of education and social skills. 
  source: https://www.sciencedirect.com/science/article/pii/S240584402101481X
  summary-type: article
  
  - title: Sex Differences in Mate Preferences Across 45 Countries: A Large-Scale Replication
  authors: various
  summary: "Men, more than women, prefer attractive, young mates, and women, more than men, prefer older mates with financial prospects. Cross-culturally, both sexes have mates closer to their own ages as gender equality increases."
  source: https://pubmed.ncbi.nlm.nih.gov/32196435/ 
  summary-type: substract, verbatim

  - title: Moderators of Sexual Interest in Opposite-sex Friends
  authors: Aleksandra Szymkow , Natalia Frankowska
  summary: Both men and women can be attracted to their opposite sex friends. Men prefer opposite sex friends that are physically attractive and more than women do. Women prefer opposite sex friends who can protect them and who can provide financial resources. Evidence suggests that this could be a manifestions of evolved human mating strategies.
  source: https://pubmed.ncbi.nlm.nih.gov/35072522/
  summary-type: abstract

  - title: Friends with benefits: the evolved psychology of same- and opposite-sex friendship 
  authors: David M G Lewis, Daniel Conroy-Beam, Laith Al-Shawaf, Annia Raja, Todd DeKay, David M Buss
  summary: More men than women report having same sex friends to enhance their social status, for athletic reasons and to get opportunity to find opposite sex partners. Women prioritize opposit sex friends who financial resources and that are physically fit. Men prioritize opposite sex friends who are attractive. This evidence suggests that opposite sex friendships may have some direct and indirect mating functions. 
  source: https://pubmed.ncbi.nlm.nih.gov/22947994/

  - title: Emotional Accessibility Is More Important Than Sexual Accessibility in Evaluating Romantic Relationships - Especially for Women: A Conjoint Analysis 
  authors: T J Wade , Justin Mogilski 
  summary: Men are more likely to break up with their romantic partners do to denial of sex. Women are likely to break up with their romantic partners due to lack of emotional availability! Emotional unavailabity is likely to lead to break ups in both sexes. 
  source: https://pubmed.ncbi.nlm.nih.gov/29867628/
  summary-type: abstract
---
{% if page.links %}
<ul>
{% for link in page.links %}  
    <li>
      <h2><a href="{{ link.source }}" >{{ link.title }}</a></h2>
      <p> Authors: {{ link.authors }}</p>
      {% if link.summary-type %}
      <p>Summary type: {{ link.summary-type }}</p>
      {% end if %}
      <p>Summary: {{ link.summary }}</p>
    </li>
{% endfor %}
</ul>
{% endif %}