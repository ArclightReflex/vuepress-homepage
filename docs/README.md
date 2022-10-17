---
pageClass: home-page
# some data for the components

name: 莫哈维飞地艺术工作室
profile: /studiologosingle.png

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/mtobeiyf
  - title: qq
    icon: "/icons/qq.svg"
    link: tencent://QQInterLive/?Cmd=2&Uin=306837749
  - title: 微信
    icon: "/icons/wechat2.svg"
    link: https://www.instagram.com

cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: 但业务范围不止艺术设计hhhhhhh
email: 306837749@qq.com ** （想要逼格的话就wy1998623@gmail.com） **
---

<ProfileSection :frontmatter="$page.frontmatter" />

## 关于工作室

我们是一个脱身于 [南京工程学院](https://www.njit.edu.cn/) ~~这是个一本！不是大专！不是大专！不是大专！~~ 的团队, 但实际上就 **三个人**  

I'm trying my best to battle with Lord Voldemort, the evil Wizard that we all fear. My research area includes Defence Against the Dark Arts and other magic. :dizzy:


## 近况

- [Sept 1991] Attended Hogwarts
- [July 1980] Born in Godric's Hollow, West Country, England, Great Britain


## 业务范围

- **Hogwarts School of Witchcraft and Wizardry** <br/>
Sept 1991 - 1997


## 项目


[完整项目经历](/projects/)

<ProjectCard image="/projects/DSC02029.JPG" hideBorder=true>

  **死亡空间1-艾萨克的工程师护甲**

  Harry P., Hermione G., *et al*
  
  Harry's wand was broken in 1997, but was repaired by him after the 1998 Battle of Hogwarts. Usually the repair of a wand is impossible, but with the use of the Elder Wand it was achievable.
  
  [[PDF](https://www.google.com)] [[arXiv](https://arxiv.org)]

</ProjectCard>

<ProjectCard hideBorder=true>

  **Harry Potter and the Deathly Hallows**
  
  In the epilogue of Deathly Hallows, which is set 19 years after Voldemort's death, Harry and Ginny are a couple and have three children: James Sirius Potter, who has already been at Hogwarts for at least one year, Albus Severus Potter, who is starting his first year there, and Lily Luna Potter, who is two years away from her first year at the school.

  [[Link](https://www.google.com)]

</ProjectCard>


## Awards & Honors

### Contests

- First place in **The Hogwarts House Cup**


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

  /* Override */
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
