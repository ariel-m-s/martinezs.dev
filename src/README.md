---
pageClass: home-page
# some data for the components

name: Ariel Martínez
profile: /profile.png

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/ariel-m-s
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com/in/amartinezs

# cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: Software Engineer
email: ariel[at]martinezs[dot]dev
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

Experienced software engineer with strong professional IT background. Demonstrated history of working in financial services and research industries. Interested in machine learning.


## News

- Feb 25, 2021 <br/>
**Platanews** –  [Startups seleccionadas para Platanus Ventures 2021-1](https://plata.news/blog/startups-seleccionadas-platanus-ventures-2021-1) <br/>
**El Mercurio** – [Platanus Ventures elige cinco startups como parte de su segunda generación](https://digital.elmercurio.com/2021/02/25/ME-I/KR3U3L1M) <br/>
**Las3claves** – [Las cinco startups seleccionadas por Platanus Ventures en su nueva generación](https://www.las3claves.com/las3claves/falabella-promete-entregar-las-compras-online-en-48-horas)

## Experience

- **Co-Founder & CTO** | Oct 2020 - Present <br/>
[Con Yappa](https://conyappa.cl), Santiago <br/>
*Latin America’s first prize-linked savings account.*

- **Software Engineer** | Mar 2020 - Mar 2021 <br/>
Glik, Santiago <br/>
*A platform for doctors to track the health of diabetic patients.*

- **Software Engineer** (internship) | Jul 2020 - Sep 2020 <br/>
[NotCo](https://notco.com), Santiago <br/>
*A Foodtech that reinvents animal-based foods using only plants.*

- **Teaching and Research Assistant** | Jun 2016 - Jul 2020 <br/>
Pontificia Universidad Católica de Chile, Santiago

## Education

- **MS in Biomedical Engineering, Bioimaging Major** | Sep 2021 - <br/>
ETH, Zürich

- **Neural Networks and Deep Learning** | Mar 2021 <br/>
Coursera Certification [[view credential](https://www.coursera.org/account/accomplishments/verify/U99YYVY72R2G)]

- **BS in Engineering, CS Major** | Mar 2016 - Jul 2020 <br/>
Pontificia Universidad Católica de Chile, Santiago

## Volunteering

- **Head of Information Technology** | May 2020 - Present <br/>
Conecta, Santiago <br/>
*A free college preparation course for high school students.*

- **Logistics Assistant** | Aug 2016 - Apr 2019 <br/>
TEDx Conferences, Santiago

- **First Responder** | May 2015 - Nov 2015 <br/>
Magen David Adom, Jerusalem and Bat Yam

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /*Override*/
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img
          width 100%
          max-width 400px

</style>
