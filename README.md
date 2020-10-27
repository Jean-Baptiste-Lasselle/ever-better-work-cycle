# Ever Better Work Cycles

_Thoughts on a design of a work cycle with a team. Started it working on a CI CD Project_

The Purpose of this repo, is for me to design, based on experience, practical recipes, to everyday manage my (team) workflow : 

* Practical, as opposed to any general theory such as "Agile", "Management theories", and even Kanban 
* Not a theory, but a recipe, or a bouquet of recipes, all being very simple : 
  * each recipe consists of defining a "work cycle" : because evertyime you work,  whatever work you do, you always end up following an ever-restarting cycle of tasks.
  * once I have made myself aware of the cycle, I can work on what tools I can use, to everyday run that cycle, with improved efficiency, and improved human relations (collaboration, think about my work mates)




# The first Draft which originated this repo


### Conclusion : What next ?

See XXXX , If we try and describe general rules, even if we restrict ourselves to "Just Gravitee APIM", things can get very quickly, very complex to comprehensively, accurately describe : 
* That's why I did not even finish toask all questions until `11 -`
* But we will need, some day, to have a comprehensive description of all strict rules /procedure, when working on _any_ dev task (feature or bugfix) on Gravitee APIM : 
  * this, as you can see, will require us to define an accurate vocabulary, a language, and its terms,  that we will use all, with the same meaning. 
  * For example, I had no choice but  defining terms like "**_Gravitee core repos_**", to ask you questions about what you wrote (to be sure i understand exactly, what I read).
  * And the work we did here, with your "Case master" draft, is a good starting point, we can keep, to finish someday, writing down all the generalized rules/procedures.
* Never the less, we do not, have today, that language, those terms, defined and well understood by all : 
  * that's Why I think that the most efficient thing to do, to go further on our work here, is : 
    * work on a first example
    * so to pick an already closed isssue, using https://github.com/gravitee-io/issues/issues?q=is%3Aclosed+is%3Aissue+author%3A%40me+ 
    * we imagine that we are back in time, when the issue was not closed, 
    * and you describe extensively, to me, what I would have to do on my machine, to close the issue, like you already did
    * With that exact example, then we can go into details, without having to define any new vocabulary, term, with their concepts, behind. You just teach me howx to do the job. that very accurate job, that issue. 
  * First, the goal is to deliver a tool used in every development environment. Ok so let's call it `gclio`, regardless of knowing if it's gonna be python or nodejs, we don't care. Now, while we are working on the _example issue_ issue that you chose [here](https://github.com/gravitee-io/issues/issues?q=is%3Aclosed+is%3Aissue+author%3A%40me+) , we can have a work cycle like this : 
    * **step 1 - ** You write a bit more, to describe and explain me how to manually solve the _example issue_ like you did, in the past, 
    * **step 1bis (optional, when you are inspired) - ** You write a bit more, in the "Development guide (Gravitee Dev Team part)" , to describe how to use tools, why automation works like this, a general guide to work on any issue, feature or bugfix, for any  gravitee dev team member.
    * **step 2 - (if there are open issue on `gclio`'s git repository)** I work on the issue of highest priority on `gclio`'s git repository : to do that, It might be neccesary, that I ask you questions, about what you wrote to describe and explain me how to manually solve the _example issue_ like you did, in the past. You write some more to answer the questions, until I can work on the issue of highest priority on `gclio`'s git repository.
    * **step 2 - (if there is no open issue on `gclio`'s git repository I can work on) ** If neccesary, I ask questions, until I can fully describe a new automation feature in a github issue on `gclio`'s git repository.
    * **step 3 - (optional, if inspired) ** If neccesary, I ask questions, until I can fully describe a new automation feature idea in a github issue on `gclio`'s git repository.
    * **constantly during cycle - ** Anytime all dev team members can open issues on `gclio`
    * **constantly during cycle - ** You and all dev team can, anytime, test `gclio`'s in the exact version of any open pull request, labelled `waiting-for-review`, folllowing pull request notes. Therefore, any pull request labelled `waiting-for-review`, must have full instructions to build, install, and test `gclio`, from the Pull Request _source branch_, on a dev team everyday machine.
    * **step 4 - ** I review all open issues on `gclio`'s git repository, to read all newly opened issues, and new messages in issues. This, to prepare questions to the dev team, in next workshops
    * **step 5 - ** during workshops together with dev team, The Dev Team : 
      * reviews all issues and pull requests on `gclio`'s git repository : decides/votes what are the most important issues, what Pull Requests are to be acepted/rejected. In other words, The Dev Team is the manager of the dev work done on `gclio`'s git repository.
      * reviews what is new newly written in "Development guide (Gravitee Dev Team part)" , discusses new "general terms" accepted as a common language for all, for example "**_Gravitee core repos_**"
     * and the cycle restarts again back at _**step 1**_
  * We do that with a first example, then a second example, then a third... :  
    * As many example as necessary, until you and all Dev Team think "OK, JB has automated everything we can dream of". 
    * Actually this is a cycle which will never end, sometimes the cycle will "roll very fast, intensely" (a workshop with all Dev Team every 3 days), to answer current  needs, and sometimes will run "as daemon" (a workshop with all Dev Team every 2 months), very ligthly. 


So as a conclusion here is an "incremental" approach I propose you, that we propose to Dev Team on next workshop, to deliver, little pieces of automation, one after the other, everytime better

All based on "true life" examples.

What do you think ?
