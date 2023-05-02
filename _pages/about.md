---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

![Cyndia at SLOPE lab](/images/cyndia_viper.png)
My name is Cyndia, and I am a PhD Candidate at UC Berkeley with the Embodied Dexterity Group. I study rover locomotion, funded by a NASA Space Technology Research Fellowship. 
<!-- In the picture above, I am assisting VIPER validation & verification testing at NASA Glenn Research Center. -->

I came to graduate school in order to develop the technical and project management skills to lead research and development groups, specifically for field robotics in challenging environments. In my research, I developed and analyzed models and simulations, which I then used to improve the operation and design of robotic systems. In the process, I had to develop performance metrics and quantification processes to evaluate success. 

In the last few years, I realized there are still huge technical challenges remaining on the path to curbing human impact on Earth's ecosystems. Many technologies have been demonstrated in the lab but struggle to be cost or energy effective in the real world. 
<!-- I am ready to combine my research and industry experience to tackle these hurdles and see these technologies to either impactful scales or to a proper localized application. -->

**My mission is to use my research experience to deploy technology from the lab into the field in order to address technical barriers to mitigating climate change, such as long-duration storage, green hydrogen generation, and carbon capture. I am a hands-on, experimentally-driven, and theory-motivated builder who enjoys adapting to the challenge at hand.**


Research Summary
======
Planetary rovers have a history of entrapment in soft Martian sand, which is difficult to visually anticipate and results in high-stakes extrication efforts. NASA will soon return to the moon to scout for water ice and other resources in polar craters, which may be composed of sloped loose regolith. As scientific objectives on Mars evolve and interest in lunar exploration increases, the need to traverse loose, sandy terrain incentivizes the design of more energy-efficient locomotion suspensions and gaits. 
To tackle this challenge, I investigated the effects of weight distribution and induced wheel slip on mobility using miniature rovers in the lab and the Volatiles Investigating Polar Exploration Rover (VIPER) mobility representative rover at NASA. 

For generating significant weight redistribution to modify the contact loads between each wheel and the terrain, I proposed the use of control moment gyroscopes and simulated the actuation levels required to improve obstacle climbing ability. Then I experimentally characterized how VIPER’s load-responsive suspension controller, which reacts relatively slowly to its environment, impacts mobility metrics. 

I also extensively applied granular resistive force theory to model wheel-terrain interaction for traversing sandy terrain. I noticed that net tractive force can be increased by inducing different levels of wheel slip across the vehicle depending on individual wheel sinkage. Using this knowledge, I was able to increase the travel velocity of a fixed suspension rover traveling through a high resistance media by 10% by driving the back wheels twice as fast as the front wheels. I found that increasing wheel slip relative to suspension kinematics in an active suspension allows an inchworming rover to climb slopes eight times more efficiently and allows VIPER to travel 35% faster in an extreme terrain sink tank. Together, these works show that there is still significant room to improve traditional wheeled planetary locomotion and that suspensions with additional degrees of control can be deployed robustly while safeguarding against entrapment.

To learn more about specific projects, please check out the Publications tab.


Personal Interests
======
In my free time, I mentor the Berkeley High School Robotics team. I enjoy watching the students' ambitions grow as they continue to achieve more each year. I hope to teach them clear and respectful communication with each other and to remind them to pay attention to and inspire those around them. I also hope we can build fun robots that challenge expectations and put on a good show.

<center> <img src="/images/frc.jpg"  width="49.5%" > </center>
<!-- <br/> -->
&nbsp;

I also love to snowboard and be outside. I enjoy foraging, hiking, backpacking, and overlanding (off-roading for people who are scared of damaging their cars).
Here are some cool pictures from the last few years.

<!-- ![](/images/fun0.png) -->
<center>
<img src="/images/fun0.png"  width="49.5%" >
<img src="/images/fun1.png"  width="49.5%" >

<img src="/images/fun2.png"  width="49.5%">
<img src="/images/fun5.png"  width="49.5%">

<img src="/images/fun3.png"  width="49.5%">
<img src="/images/fun4.png"  width="49.5%">
</center>

<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->

<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)



https://user-images.githubusercontent.com/6529420/235712812-89b1f236-42f0-4d15-b04c-f506fa5da39e.mov

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
