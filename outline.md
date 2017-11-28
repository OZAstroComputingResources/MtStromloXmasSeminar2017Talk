---
title: "Astronomy and “eResearch”: My Journey"
author: James Tocknell
progress: false
...

![We all use computers in astro](images/Femputer.png)

---

But few of us have been taught the necessary skills…

---

I’m going to cover what I think everyone needs to know

. . .

And how I learnt these skills.

---

![](images/python.png)

---

# Use version control for everything
 * Scripts, code, papers, everything
 * github/bitbucket/gitlab have free private repos for students/academics

---

# Use a package manager
[conda](https://conda.io/docs/), [spack](https://spack.io/),
[pip](https://pip.pypa.io/), apt, [homebrew](https://brew.sh/),
[chocolatey](https://chocolatey.org/)

# Package your code
 * Python: [Python Packaging User Guide](https://packaging.python.org)
 * Fortran/C/C++: [autotools](https://en.wikipedia.org/wiki/GNU_Build_System), [cmake](https://cmake.org/)
 * See [https://swcarpentry.github.io/managing-research-software-projects/](https://swcarpentry.github.io/managing-research-software-projects/)

# Manage your data
[![](images/datalad.png)](http://datalad.org/)

# Automate
   * [Make](https://swcarpentry.github.io/make-novice/)
   * [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/)
   * Testing—see [https://katyhuff.github.io/python-testing/](https://katyhuff.github.io/python-testing/)

---

So how to learn more?

---
# Courses
[![](images/software-carpentry.png)](https://software-carpentry.org/)
[![](images/adacs.png)](https://adacs.org.au/)

# Books
  * [Effective Computation in Physics](http://physics.codes/)
  * [Python Cookbook](http://shop.oreilly.com/product/0636920027072.do)

# Other people/Meetups
   * [Coffee and Code @ MQ](https://github.com/OZAstroComputingResources/MQCoffee-CodeResources)
   * [Hacky Hour @ UQ](https://hackyhourstluc.wordpress.com/)
   * Other unis?
   * [ResBaz](https://resbazblog.wordpress.com/)

# Internet
   * Stackexchange (stackoverflow, tex, unix, and more)
   * [The Hitchhiker’s Guide to Python](http://docs.python-guide.org/en/latest/)
   * [Python Module of the Week](https://pymotw.com/3/)
   * [Scipy Lectures](http://www.scipy-lectures.org/)
   * [PyVideo](http://pyvideo.org/)
   * Blogs: [Python Planet](http://planetpython.org/)
   * Project documentation

# Questions?
See https://aragilar.github.io/MtStromloXmasSeminar2017Talk/ for slides

# Other resources
 * [autotools book](https://www.nostarch.com/autotools.htm) [autotools advice](https://autotools.io/index.html)
 * [unix advice](https://yakking.branchable.com/) [and more](http://programmer.97things.oreilly.com/wiki/index.php/97_Things_Every_Programmer_Should_Know)
 * [Why not csh](http://www.faqs.org/faqs/unix-faq/shell/csh-whynot/)
 * [reproducable research](https://mg.readthedocs.io/reproducible_research.html)
 * [how to report bugs](https://www.chiark.greenend.org.uk/~sgtatham/bugs.html)
 * [git for ages 4 and up](https://www.youtube.com/watch?v=3m7BgIvC-uQ)

# Why not conda?
 * See [KERN paper](https://arxiv.org/abs/1710.09145) for why they didn’t use
   conda
 * Not everything in conda (hence KERN)
 * Not as powerful as other systems (e.g. Spack, [nix](https://nixos.org/nix/))
 * Does not work with some python tools
 * Try conda, but be aware of alternatives
