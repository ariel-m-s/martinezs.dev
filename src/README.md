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
email: ariel[at]martinezs[dot].dev
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

Experienced software engineer with a demonstrated history of working in financial services and research. Strong information technology professional with a BS in Engineering focused in Computer Science.

<!-- ## News

- [Sept 1991] Attended Hogwarts
- [July 1980] Born in Godric's Hollow, West Country, England, Great Britain -->

## Education

- **BS in Engineering, CS Major** | Mar 2016 - Jul 2020 <br/>
Pontifical Catholic University of Chile, Santiago <br/>

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
