---
theme: bricks
title: Openquest 2025 | Akash Santhosh
drawings:
  persist: false
transition: slide-left
mdc: true
layout: center
seoMeta:
  # By default, Slidev will use ./og-image.png if it exists,
  # or generate one from the first slide if not found.
  # ogImage: https://raw.githubusercontent.com/akash-santhosh/.com/refs/heads/master/akash/images/debconf_talk.jpg
ogImage : https://raw.githubusercontent.com/akash-santhosh/.com/refs/heads/master/akash/images/debconf_talk.jpg
---

# FOSS and Hacktoberfest

Presentation slides for openquest

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Let's dig in <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  </div>

---
layout: center
---

 Who am I


## I'm Akash Santhosh

- (googling might help but the photos are the actor Aakash Santhosh)
- my usernames are my fullname mostly
- Network Engineer by Profession
- Network, Systems and Cloud
- Debian Developer (#DebianUyir)


<a href="https://aks.one" target="_blank"
  class="abs-b m-6 text-xl !border-none">aks.one
</a>

---
transition: fade-out
---

# What is FOSS?
### FOSS = Free and Open Source Software
##### It’s built around the Four Freedoms:

<v-clicks>

-  🏃 **Freedom 0** - Freedom to run the program as you wish, for any purpose.
-  📖 **Freedom 1** - Freedom to study how the program works and change it so it does your computing as you wish.
- 🧰 **Freedom 2** - Freedom to redistribute the copies with others. Access to the source code is a precondition for this.
- 🛠 **Freedom 3** - Freedom to share modified versions to others. By doing this you can give the whole community a chance to benefit from your changes. Access to the source code is a precondition for this.

</v-clicks>

##### The idea is that access to source code is essential for freedom and collaboration.
<br>
<br>

Read more about [FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software)

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
transition: slide-up
level: 2
---

# Open Source Sofware

We are talking about Open Source Software but we need to know what is what
## Open Source vs Free Software

|                                                     |                             |
| --------------------------------------------------- | --------------------------- |
| Free Software                 | focuses on users’ freedom. |
| Open Source Software          | focuses on the way software is developed and distributed. |

Licenses can be protective (copyleft) or non-protective (permissive).

<v-click>

<span v-mark.circle.organge="2">All free softwares are open source</span>. But all open source softwares are <span v-mark.red="3">not free</span>.

</v-click>

---

# Free Software vs Open Source vs Proprietary

| Feature / Aspect       | **Free Software (FSF)**                         | **Open Source (OSI)**                               | **Proprietary Software**                     |
|-------------------------|-------------------------------------------------|-----------------------------------------------------|----------------------------------------------|
| **Source Code Access**  | ✅ Yes (must be available)                      | ✅ Yes (must be available)                          | ❌ No                                        |
| **User Freedoms**       | ✅ Full 4 Freedoms (use, study, share, modify)  | ⚠️ Yes, but may have restrictions depending on license | ❌ None (limited by license)                  |
| **Philosophy**          | Ethical: about **freedom** and user rights      | Practical: about **collaboration & efficiency**     | Business-focused: about **control & profit** |
| **Examples**            | Debian, LibreOffice, VLC, Blender               | MongoDB (SSPL), Elasticsearch (SSPL), Redis modules with Commons Clause | Microsoft Office, Adobe Photoshop, Apple iOS |


---

# Free Software vs Open Source vs Proprietary

| Feature / Aspect       | **Free Software (FSF)**                         | **Open Source (OSI)**                               | **Proprietary Software**                     |
|-------------------------|-------------------------------------------------|-----------------------------------------------------|----------------------------------------------|
| **Can Sell?**           | ✅ Yes (you can charge for free software)       | ✅ Yes (depends on license)                         | ✅ Yes (main revenue model)                   |
| **Can Modify?**         | ✅ Yes, with redistribution rights              | ✅ Yes, with license compliance                     | ❌ No (illegal without permission)            |
| **Community Involvement** | ✅ High (freedom-focused communities, FSF, GNU) | ✅ High (GitHub/GitLab, corporate + community mix)  | ⚠️ Limited (beta testing, closed feedback)    |
| **Control**             | Users have control                             | Shared between community & companies                | Vendor has full control                       |


---
layout: image-right
image: https://raw.githubusercontent.com/akash-santhosh/.com/refs/heads/master/akash/images/thar.jpg
---

# Does FOSS make any sense ?

Imagine a car you own

---
layout: image-left
image: https://raw.githubusercontent.com/akash-santhosh/.com/refs/heads/master/akash/images/hood.jpg
---

# Does FOSS make any sense ?

Imagine a car you gonna buy

---
level: 2
---

# Why contribute to Free Software

- Made with Passion/love.
- The world runs on free software.
- Amazing developer community.
- Digital Privacy is possible only through free software.
- By being part of a free software project you get to be a part of a movement bigger than yourself, the consequences if which extends to millions of users.

## Minor Perks

- Build your experience and skills working for real life projects.
- Contributions are public hence verifiable.
- Fame and Recognition.
---
foo: bar
dragPos:
  square: 685,212,165,_
---

# How to contribute to free software ?

1. 1.Become a user.
2. 2.Find something you like.
3. 3.Join the community.
4. 4.Go through the issues page.
5. 5.Start small and always ask doubts.
6. 6.Slowly familiarise yourself with the technology used.
7. 7.Become part of the team!

<img v-drag="'square'" src="https://upload.wikimedia.org/wikipedia/commons/0/04/Debian_logo.png">

---

# Hacktoberfest

- What is Hacktoberfest ?
- Why should you participate ?
- Why does it exist ?

---

# For Individuals

- **Learning by doing**: You get hands-on experience with real-world codebases.
- **Skill development**: Improve coding, documentation, collaboration, and version control (Git).
- **Networking**: Connect with global developers, mentors, and organizations.
- **Portfolio boost**: Your contributions are visible on GitHub → helps in job applications.
- **Recognition**: Being listed as a contributor to popular projects gives credibility.
- **Rewards**: Hacktoberfest offers swag + the satisfaction of giving back to the community.

---

# For the Community

- **Shared innovation**: Multiple contributors improve and maintain projects.
- **Faster development**: Bugs fixed and features added quickly by the community.
- **Accessibility**: Free tools for people, schools, startups, and non-profits.
- **Diversity of ideas**: Contributors from different backgrounds bring unique perspectives.

---

# For Companies

- **Cost savings**: No expensive licenses.
- **Security**: Open code → more eyes checking vulnerabilities.
- **Talent pipeline**: Recruit skilled contributors who already understand the project.
- **Ecosystem growth**: Builds trust and brand recognition in the tech world. 

---

# Hacktoberfest & Career

### Portfolio Building
- Every contribution (PR, issue, documentation fix) you make shows up on your GitHub/GitLab.
- Recruiters look into contributions

### Practical Experience
- Learn the method
- Experience collaborating on different teams.

### Networking & Community
- You get noticed by project maintainers, who are often professionals at big companies.
- This can lead to something more.

---

# Hacktoberfest & Career

### Demonstrates Initiative
- Employers like people who go beyond coursework and engage in open-source.
- Contributions on paper

### Stepping Stone to Bigger Contributions
- Becoming Maintainers
- Outreachy and Summer of Code

### Limitations
- One month of PRs alone won’t get you hired.
- Low-quality or “spammy” PRs won’t impress recruiters.

---
layout: center
class: text-center
---

# Anything else 👀 ???


---
layout: center
class: text-center
---

# Thank you

[Website](https://aks.one) · [Portfolio](https://akashsanthosh.com) · [Debian](https://nm.debian.org/person/akash)

## Akash Santhosh

connect me at

IRC: akashsanthosh

Matrix: akashsanthosh:matrix.org

Mail: akashsanthosh@disroot.org | akash@debian.org
