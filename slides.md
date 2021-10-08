---
class: text-center
theme: light-icons
layout: center
---

# FOSS, Hacktoberfest 👀

slides for Hacktoberfest

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Go <carbon:arrow-right class="inline"/>
  </span>
</div>

<a href="https://aks.one" target="_blank"
  class="abs-br m-6 text-xl !border-none">Akash Santhosh
</a>

---
layout: image-right
equal: true
image: https://aks.one/hotlink-ok/end.jpg
---
Hello There

# I'm Akash Santhosh
- I love networks and community
- does web, cloud, servers
- works on networks and security
- find me online on aks.one


---
layout: center
equal: true
---
# What is FOSS ?
---
layout: center
equal: true
---

# The Four Freedoms

Free and Open Source Software is any piece of software that respects their
  user’s four freedoms:
- **The freedom to run the program as you wish, for any purpose (freedom 0)**

- **The freedom to study how the program works, and change it so it does your
    computing as you wish (freedom 1).** 

-  **Access to the source code is a precondition for this. The freedom to
    redistribute copies so you can help others
    (freedom 2).**

- **The freedom to distribute copies of your modified versions to others
    (freedom 3). By doing this you can give the whole community a chance to
    benefit from your changes. Access to the source code is a precondition for
    this.**

<br>
<br>

---
equal: true
image: 
---

# Open Source vs Free Software

- **Free Software is about user’s freedom.**

- **Open Source is a way of making software.** 

- ‍**Protective vs Non-Protective Licenses.**

# Open Source vs Proprietary Software

- **OSS can be used for any purpose.**
- **OSS Allows to study how software works.**
- **OSS has Freedom to modify and improve the program.**
- **OSS No restrictions on redistributions.**
- **Proprietary has Restrictions on sharing of software illegally**
- **Proprietary has Time period up to which software will operate**
- **Proprietary limits Number of features allowed to use**
---
layout: center
equal: true
---

# Why contribute to FOSS?

Why should I consider contributing to free software?

- **Amazing developer community**

- **The world runs on free software.** 

- ‍**Digital Privacy is possible only through free software.**

- **By being part of a free software project you get to be part of a movement 
<br>bigger than yourself the consequences if which extends to millions of users.**

Minor Perks:

- **Build your experience and skills working for real life projects** 

- ‍**Contributions are public hence verifiable.**

- **Fame and Recognition**
<br>
<br>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
equal: true
---

# Git

A Short History of Git

The Linux kernel is an open source software project of fairly large scope. During the early years of the Linux kernel maintenance (1991–2002), changes to the software were passed around as patches and archived files. In 2002, the Linux kernel project began using a proprietary DVCS called BitKeeper.

In 2005, the relationship between the community that developed the Linux kernel and the commercial company that developed BitKeeper broke down, and the tool’s free-of-charge status was revoked. This prompted the Linux development community (and in particular Linus Torvalds, the creator of Linux) to develop their own tool based on some of the lessons they learned while using BitKeeper. Some of the goals of the new system were as follows:

- Speed
- Scalability
- Simple Design
- Fully distributed
- Being free and open source
- Strong support for non-linear development (thousands of parallel branches)
<br>
<br>

---
layout: center
equal: true
---

# GitHub

History of github

Development of the GitHub platform began on 1 October 2007. The site was launched in April 2008 by Tom Preston-Werner, Chris Wanstrath, and PJ Hyett after it had been made available for a few months prior as a beta release.<br>

When Chris and Tom started working on GitHub in late 2007, Git was largely unknown as a version control system.There were no commercial Git hosting options whatsoever.And so GitHub was created to provide developers the option to host code securely and manage commits to code in proper manner.
Soon the adoption of github for managing opensource projects grew rapidly due to which paid git hosting became a viable option and paid subscriptions made the project profitable.The software that runs GitHub was written using Ruby on Rails and Erlang.<br>

Simon Oxley designed the octopuss, alongside the white bird Twitter used (before they received a proper logo) as part of a usual routine of cranking out images for iStock. GitHub saw it, and wanted it, presumably under the notion that it can represent how complex code combines to create peculiar things, much like the octopuss…except the CEO of GitHub called it an octocat, and it has been the octocat since.

---

preload: false
---


<div class="w-60 relative mt-6">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-square.png"
    />
    <img
      v-motion
      :initial="{ y: 500, x: -100, scale: 2 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-circle.png"
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>

  <div 
    class="text-5xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Hacktoberfest
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 40, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }">

  - Hacktoberfest is a month-long celebration of open source software <br>run by DigitalOcean in partnership with Appwrite, Intel and DeepSource.
  
  - The goal of the event is to encourage participation in the open-source community all across the globe.
  
  - Pull requests can be made in any participating GitHub or GitLab hosted repository/Projects. <br>Look for the 'hacktoberfest' topic to know if a project is participating in Hacktoberfest.

  - You can sign up anytime between October 1 and October 31. Just be sure to <br>sign up on the official Hacktoberfest website for your pull requests to count.


</div>

<a href="https://aks.one" target="_blank"
  class="abs-br m-6 text-xl !border-none">Akash Santhosh
</a>

<a href="https://aks.one" target="_blank"
  class="abs-b m-6 text-xl !border-none">aks.one
</a>
---


# **Terms and Details**

- The pull request must contain commits you made yourself.

- If a maintainer reports your pull request as spam, it will not <br>be counted toward your participation in Hacktoberfest.

- If a maintainer reports behavior that’s not in line with the <br>project’s code of conduct, you will be ineligible to participate.

- A pull request is considered approved once it has an overall <br>approving review from maintainers, or has been merged by <br>maintainers, or has been given the 'hacktoberfest-accepted' label.

- Maintainers determine if their open-source projects <br>participate by adding the ‘hacktoberfest’ topic.

- Quality pull requests submitted on GitHub and GitLab are rewarded.

- Engaged maintenance of Hacktoberfest tagged repositories are rewarded.

---
layout: center
equal: true
---

# **The Great blank space...**

<a href="https://aks.one" target="_blank"
  class="abs-br m-6 text-xl !border-none">Akash Santhosh
</a>

---
layout: dynamic-image 
image: 'https://aks.one/end.jpg'
class: text-center
---

# Thank You

## Akash Santhosh

[Engineer](https://aks.one) / [Evangelist](https://github.com/akash-santhosh)

<a href="https://aks.one" target="_blank"
  class="abs-br m-6 text-xl !border-none">aks.one
</a>
