---
layout: default
---

{% capture site_header %}
{% capture site_header_body %}
## Docker Training

by [__Ondrej Sika__](https://ondrej-sika.com)
{% endcapture %}
{% include site-header.html body=site_header_body button1href='/' button1text='Register for training' button2href='/' button2text='Contact me' logo_url='/d.png' %}
{% endcapture %}
{% include section.html content=site_header %}



{% capture actual_courses %}
## Actual Courses

{% include table.html table=site.data.actual_courses %}
{% endcapture %}
{% include section.html content=actual_courses %}



{% capture about %}
## About Docker

Docker is container platfor which provide strictly defined and separated enviroment for run your application. Docker has many advantages, you have full control of environment of every part of your application. You can use somewhere Debian, otherwhere Cent OS, and host it on one server. Docker also provide security level to separate every application from one large system to many microservices on one host. Containers will se just what you grant them.
{% endcapture %}
{% include section.html content=about %}

{% capture clients %}
## My Clients

{% include clients-logos.html clients=site.data.clients_logos %}
{% include clients-recommendations.html recommendations=site.data.clients_recommendations %}
{% endcapture %}
{% include section.html content=clients %}

{% capture agenda %}
## Course Agenda

- What Docker is, why use Docker and it’s advanages & disadvanages
- How to install Docker and basic terminology
- Docker registry and running containers
- Building own images
- Multi-container aplications and Docker Compose
- Docker Machine - Docker host manager
- Docker Swarm - Docker’s native cluser
- Deployment into the Swarm
- Production setting of Docker
- Container monitoring a management in production
- Basic usage in CI (Continues Itegration)
{% endcapture %}
{% include section.html content=agenda %}


{% capture pricing %}
## Pricing

{% include pricing.html plans=site.data.pricing %}

Students, Universities and non-profit organisations have 50% discount.
{% endcapture %}
{% include section.html content=pricing %}



{% capture contact_col1 %}
### Ondrej Sika
<ondrej@ondrejsika.com>
<br>+420 773 452 376

##### Katerina Lipovska (Assistant)
<katerina@sikahq.coma>
{% endcapture %}

{% capture contact_col2 %}
<ul>
<li><a href="https://www.facebook.com/sikaondrej">Facebook</a></li>
<li><a href="https://twitter.com/ondrejsika">Twitter</a></li>
<li><a href="https://github.com/ondrejsika">Github</a></li>
<li><a href="https://www.linkedin.com/in/ondrejsika/">Linkedin</a></li>
<li><a href="https://navolnenoze.cz/prezentace/ondrej-sika/">Na Volne Noze</a></li>
</ul>
{% endcapture %}

{% capture clients %}
## Contact me
{% include col-2.html col1=contact_col1 col2=contact_col2 %}
{% endcapture %}
{% include section.html content=clients %}


{% capture about_me_col1 %}
Jmenuji se Ondrej Sika, pracuji jako software engineer na Slush Poolu (tezba Bitcoinu) a vyvojem software se zabyvam od roku 2009. Od roku 2013 skolim. Vsechny moje kurzy stavi na mych dlouholetych znalostech a zkusenostech z vyvoje, testovani a provozovani softwatrovych projektu od malych webu po velke globalni projekty. Nastroje jako Git, Docker nebo CI pouzivam na denni bazi, vse co skolim jsem pouzil v realnych projektech a mam s technologii osobni zkusenost. Vsechny kurzy jsem schopen upravit na miru vasim pozadavkum a vsechny probihaji formou workshopu – verim ze si neco zkusit je ta nejefektivnejsi cesta se neco naucit. Zaroven jsem otevren spolupraci jako externi lektor, pokud jste skolici firma a hledate nekoho kdo vam bude skolit temata jako Git, Docker, CI … (vlastne cokoliv co nabizim), tak se urcite domluvime. Vice infomaci naleznete zde: Lektorska Spoluprace. Vsechny kurzy a skoleni delam v ceskem nebo anglickem jazyce. Rad fotim a pisi blog o technologiich, cestovani a knihach.
{% endcapture %}

{% capture about_me_col2 %}
<img src="/ondrejsika3-300x300.jpg" class="img-fluid">
{% endcapture %}

{% capture about_me %}
## About me
{% include col-2.html col1=about_me_col1 col1cls='col-sm-9' col2=about_me_col2 col2cls='col-sm-3' %}
{% endcapture %}
{% include section.html content=about_me %}
