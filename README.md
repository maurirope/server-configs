<h1 align="center">server-configs</h1>
<h2 align="center">A repository to store example case scenarios of ubuntu server configuration documents or scripts </h3>

---

## Background

Putting together configuration examples became a necessity for me when I fell victim to a DDoS attack, the aftermath of a previous brute-force SSH intrusion by foreign actors. Back then, my younger self failed to grasp the potential risks of publicly exposing services and the sheer volume of "suspicious traffic" circulating on the interwebs, both black-hat and white-hat.

The attack, disruptive enough to halt the services I relied on, fortunately, didn't result in any data loss. This incident taught me a valuable lesson: the first rule before exposing anything online is to evaluate the risk and assess what could be lost if an attack occurs.

Guided by my HL7 certified uncle during my pre-teens and teenage years, I was familiar with terms like *iptables, ufw, fail2ban, nginx,* and I thought diving into the world of Linux would be like entering a secure playground. How wrong I was...

It often takes a bit of running around, to find out. However when I finally got myself up to the task of implementing stronger security, instead of running-around, it had me twirling-around, dizzy and disoriented. Turns out, the journey from big words to secure systems is like a high G-force ride, leaving me with a head full of spins and a newfound respect for the intricacies of Linux security.

## What's in it for me?

An easy-to-understand, well-documented, case-scenario-specific, unique configuration file — almost good enough for Copy&Paste (except for the data you must provide on your own). This helps you avoid extensive documentation investigation sessions.

These configuration files are not readily available elsewhere, often being a combination of multiple files extracted from different sources or a de-cluttered version of the original default file.

**These files are solution-centric.** The approach is not to delve into the entire software solution. Many of these programs are versatile and powerful, with an entire ecosystem of certifications.
Therefore, the focus is to keep it **as simple as possible** to achieve the desired outcome, maintaining some fair standards of security *(for a home-lab)*, while still guiding towards additional resources and an understanding of the underlying technologies.

## What will this project look like in the future?

I have uploaded some basic .conf's from where I have removed my personal information to start the repository. The idea for now is to finish documenting everything I currently run at my home-lab and improve the documentation to include external references to the solutions provided. 

My wish for the future is to be able to expand this into a community library of code snippets for SysAdmins/DevOps or you everyday server owner enthusiast, where folks can submit their snippets and/or provide support, updates and bug-reports.

## Feedback
Thanks for visiting and reading my story thus far! 
I hope that you can find something useful for you here, or that you can find a way to contribute by sending PRs or issue reports.

Mauricio R.