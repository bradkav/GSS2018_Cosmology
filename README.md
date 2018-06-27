# GSS2018_Cosmology

This is the repository for Group 1, covering the topic of *Dark Matter in Cosmology*. See the main repository - [GRAPPA_Student_Seminar_2018](https://github.com/bradkav/GRAPPA_Student_Seminar_2018) - for more information.

In particular, for information about the scripts, [see here](https://github.com/bradkav/GRAPPA_Student_Seminar_2018/wiki/Scripts).

Use the `review/` folder for the LaTeX files for your review and the `scripts/` folder for your code.

-----------------

### Plan for the review

* Add a section on possible particle physics solutions to the 'Cracks in LCDM' (self-interacting DM, fuzzy DM, warm DM, etc.) - what simulations have been done and how do they solve these problems?
* Add a (short) section discussing discrepancies between local estimates (from measurements of Type 1a Supernovae) and global estimates (from cosmology, e.g. the CMB) of the Hubble parameter H0 (e.g. arXiv:1607.05617).
* Add a discussion of the radial acceleration relation (see the slides). You can discuss what is observed, as well as what simulations say about whether a LCDM universe can reproduce these observations.


### General comments/feedback

* Can add a short discussion of inflation, but nothing too detailed. The discussion should be more focused on 'setting the stage' for the CMB (that inflation gives us the initial fluctuations which seed the structure of the universe). 
* Make sure to distinguish between the CMB and BAO (the latter is typically discussed as a feature observed in large scale clustering of galaxies). Note of course the common origin of the CMB and BAO.
* Improve the discussion of simulations. Make clear the physical distinction between different simulation techniques. How does SPH differ from AMR? Which other codes are used? E.g. "moving mesh" techniques? What is the state of the art? How is "sub-grid" physics included? What are the uncertainties in these "sub-grid" physics models which account for feedback?
* Add a discussion of Big Bang Nucleosynthesis (BBN) as evidence 'against' baryonic dark matter.
* **[22/06]** Could mention that rotation (as in, rotation curves) is observed not just in stars but also in gas (neutral hydrogen): arXiv:0810.2100
* Smoothed particle hydrodynamics - arXiv:1007.1245

Email if you need some more guidance! We can also give you some more feedback on Friday.

### Comments on the scripts

It doesn't look like you've uploaded your scripts, so make sure you do that by the end of the course! From what we've seen in the scripts sessions so far, it looks like you're doing well, but here are a few suggestions/hints anyway:

* Don't be afraid to add some markdown cells so that you can add text/latex to your notebooks. You can add explanations so that people know what you're doing and add some equations (equations of motion, hubble rate, whatever). Try to tell the story so that people can follow.
* Try to save some figures (use `savefig` in `matplotlib`) so that people can see the plots even if they don't want to run the notebook. Similarly, if your code takes a long time to run, try to save the output (use `numpy.savetxt') so that you can load and plot the results later. That way you don't have to rerun the slow computations every time!
