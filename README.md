Well I work in tech, for a bunch of time now, but still think it is difficult to prepare newcomers to deal with git errors, <strike>partially because the new generation doesn't have the attention time span to read</strike> the messages, that are quite good.

I am looking for a way to develop a training material that goes beyond the init/commit/pull/push, that try to cover all those situations in which junior developers simply copy their  changes to another folder, delete e re-clone the repo and try to restore their evolution.

So **do you have any suggestions on good training for pitfalls on Git?** 

Being more specific:

I am thinking in a collections of repo states that are challenging, and could lead to inexperienced developer to panic, alongside with tips or instructions on how to evade/solve the problems.

The format I am alluding is:

  1. A zip file with a standalone repo (non remote defined), with a sample code, in a challenging situation to be solved **and**
  1. a CHALLENGE_README.md with sections for tips, and another section for a step by step solution
  1. some example code (I really suggest a poem in a .md file, since it does not require almost any extra knowledge on any programming concept), the conflict could be on a branch with plurals, and another with genre switch.

Must be a zip file, since it is ubiquitous, present on most OSs and able to contain, for instance a failed rebase, or cherry-pick, among other scenários.

I started this git repo, ironically, to ask for help to create such a learning resource.

