---
layout: post
title:  "Welcome to Triche Lab!"
date:   2021-05-21 14:53:03 -0400
categories: jekyll update
---
##2021 onboarding: less bad than 2020


    *Are you new to the lab?*
    If so, <a href="#PBL">skip right to your first task</a>, then come back. 

#Expectations
      My job is to ensure that the lab can do worthwhile science. Your job is
      to do worthwhile science, and answer interesting questions. Both our jobs 
      require regular communication and feedback.

      You must check in (via Slack or otherwise) M/W/F at 9AM, unless
      we have previously made other arrangements. Monday check-ins are
      to discuss and set individual weekly goals; Wednesdays are meant as
      a milestone where we communicate progress towards Monday's goals; 
      Friday check-ins serve as a venue for everyone to briefly summarize
      the week's progress and to address matters arising.
        
        
**I must schedule a 1:1 with you (in person, Zoom, call, whatever) every 2 weeks. These can be rescheduled but must not be skipped.**
	  A 1:1 meeting is for long-term goals (fellowships, grants, papers, 
	  career choices), calibrating expectations, and to ensure our working
	  arrangement remains mutually beneficial. If you are unfamiliar with 
	  [Simone's Maxims](https://clincancerres.aacrjournals.org/content/5/9/2281),
	  please read them now
		
      **Everyone must attend lab meetings on Fridays at 12pm. If you**
      **have a conflict, please let Tim, Mary, and Lauren know so we can**
      **try to accommodate. Slack is for day-to-day lab business; lab meeting**
      **is structured to keep us all focused on short- and medium-term goals.**
      **Lab members who are not presenting in a given week are responsible for**
      **listening carefully, and providing useful feedback to those who are.**
      **Lab members whose turn it is to present are expected to do so, or swap**
      **slots with another who will. This is important to maintain focus.**
      **Progress is our most important product.**
        
      **Finished is better than perfect** Weekly presentations enforce
      this basic concept: successful projects hit milestones and produce 
      insights, tools, or both, often in ways that we could not have 
      anticipated. This can't happen if we don't communicate, with each
      other and with the world at large, via publication and presentation.
         
      **Successes are worth celebrating.** Manuscript submission, 
      preprint deposition, formal journal acceptance, invitations to present
      at major venues, notice of awards, lab birthdays and lab babies -- 
      they all matter. Science is hard enough without ascetism. You might
      need to remind me -- please do. I will pick up the tab (duh? But
      better to spell it out than assume anything). If you can give Lauren
      a bit of lead time, we can plan more interesting outings accordingly.
       
##Preliminaries
	
    Mostly reading you can do at home or before rotating/interning/etc.
    We are a wet and dry lab, so we have some background suggestions for both. 
    

###Dry
    The dry background changes but, assuming you have some familiarity with 
    programming, statistics *(machine learning, data science, whatever)*,
    and experimental design, the following are good starting points:
    
    **Data- and compute-intensive inference (stats/ML/data science):
    [Modern Statistics for Biology](http://web.stanford.edu/class/bios221/book/)
    Other useful starting points exist (ISL/ESL, data science titles in 
    python, etc.). There is nothing wrong with using a VAE or *NN to learn 
    a model, but there is also no benefit to using one when a simpler model
    offers 99.9% of the benefit with 0.01% of the cost. Holmes &amp; Huber
    do a great job of connecting fundamentals to modern machine learning 
    approaches, with worked examples including figures.

    **Functional/epigenomic analysis (ChIPseq/RNAseq/BSseq):
    [Computational Genomics in R](https://compgenomr.github.io/book/)
    Altuna does a GREAT job explaining matrix factorization, for example, 
    and there is an unusual emphasis on DNA methylation analysis, which 
    can be helpful when looking at cell-free nucleic acids (for example). 
    Some of the multivariate models for sequential data (notably ChromHMM) 
    are treated very briefly, but you can read the papers for those, or
    supplement with something like [Stanford CS271](https://www.udacity.com/course/intro-to-artificial-intelligence--cs271)

    **Single cell sequencing analysis (plate-seq is similar to bulk):
    [Orchestrating Single Cell Analyses](https://bioconductor.org/books/release/OSCA/)
    The general principles are the same in R and Python, and in fact 
    we go back and forth between the two quite regularly (e.g. 
    [velocessor](https://github.com/trichelab/velocessor) calls
    [scvelo](https://github.com/theislab/scvelo/) ).
    Many if not most of the same principles apply to flow, CyTOF, and CITE,
    which is handy, since we index sort and compare to all of the above.

###Wet
    
    The 3-volume set of Molecular Cloning is in bay 16, and the videos for 
    various (strange and/or wonderful) protocols are on Google Drive, which 
    is something to which you ought to have access. If not, email Mary. If you
    have specific protocol questions, email Mary, or whoever optimized the
    protocol. For context ("why are you doing this"), Tim may or may not be
    a useful source. For practical wet bench questions, ask Mary. 
    
###Neither/Both 
    
    For papers, proposals, and general reference, we like Google Docs and 
    Paperpile (the latter in part because some or all of a person's references
    can be shared and synchronized easily with others, as with Tim's own pile 
    and the trichelab Paperpile account). The "shared" account is meant to 
    facilitate "live" links and bibliographies in collaborative work; if you 
    end up using Paperpile continuously for proposals and reference storage,
    we will get another license for your personal use (just ask). 
    

##Random tips/insights/suggestions
    Use screen/tmux for interactive sessions so you don't lose work.
    
    The sooner you package your code, the easier your life will become:
    
      1. If you may ever need script again, put it in GitHub.
      2. If you use a piece of code twice, make it a function
      3. If you use a function thrice, make it into a package or library
      4. If other people use your functions, aim at CRAN, pypi, or BioC.
    
    Good habits help prevent bad situations, at the bench or the keyboard.
    
    Develop good habits whenever you can. The best way I know of to make
    code, experiments, and manuscripts (work products) reproducible is to 
    automate them, ideally via continuous integration (for code products).
    
    We did this for Arkas, Bioconductor does it for R packages, Casey's lab did 
    it for analyses, and GitHub Actions can do it for your code/analyses. It 
    sucks to set up but, for big projects, it's a lot better than trying to 
    recreate everything when a reviewer squawks 18 months from now.
    
#Finished >> perfect 
    
    Sometimes you will need to compromise in order to hit a deadline or
    present in a timely manner. That's fine. The goal of developing good habits 
    is to ensure that you can finish projects, not to strive for perfection.
    **Finished is better than perfect.** But don't fool yourself about 
    whether a project is finished -- our job is to communicate useful advances
    to the rest of the world, so *we have to publish the results.*

#PROBLEM BASED LEARNING OPPORTUNITY!
     
    First things first, if you're doing dry work, you'll need a GitHub ID.
      
        
    set up a [GitHub](https://github.com/) account, 
    if you don't already have one
        
    join the [trichelab](https://github.com/trichelab/)
    organization on GitHub

    Fork the repository trichelab.github.io (these pages) to your account,
    edit it (I don't care what you edit, just do something useful), 
    `git add`, `git commit`, `git push`, and open a pull request against 
    the parent (trichelab) repository to merge the changes (or not). 


    Find someone to code review the merge.  Congratulations, you're a 10x 
    dry lab developer!  (or not... but at least you passed 'hello world') 


    Notes: 

        Please don't get us sued if you can help it. 
        Feel free to migrate this dumpster fire to Jekyll or something pretty.

    Some theftworthy lab onboarding pages:

    -[Casey Greene's Lab](https://github.com/greenelab/onboarding/blob/master/onboarding.md) 
    -[Elana's lab](https://fertiglab.com/)
    
    What all else can we drag in?  Surely there's rather a lot.
    
    *What kind of computer/OS should I use for dry lab stuff?*
    That all depends -- if you're going to build R packages, just use Linux.
   
    The Linux Subsystem for Windows version 2 (LS2) can be enabled on Windows.
   
    If you're a normal human being, you can use Mac OS X, but it'll be rough if
    you later decide to maintain a Bioconductor package (looks good on your CV):
  
    >
      The lack of Mac binary packages for R-devel on CRAN together with the
      high turnover of Mac OS versions are a major PITA and the reason why
      when R/Bioconductor newbies ask me what OS I recommend for package
      development I always say Linux, without hesitation. Unless they want to
      suffer ;-)

   -[Herve Pages](https://stat.ethz.ch/pipermail/bioc-devel/2020-January/016010.html)

    # universal truths about hardware

    Whatever you use, put a lot of RAM in it, and execute your long-running 
    jobs on HPC or AWS so that you don't lock up your own machine and miss 
    deadlines, panic, etc.  Local machines are for exploration and development, 
    ONLY, and if you don't have multiple copies/backups of code/data/documents
    (ideally version controlled), it must not be very important.  



    Students, staff, trainees: add what you like here. *and open a PR*


