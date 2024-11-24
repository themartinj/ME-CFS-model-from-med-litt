# ME-CFS-model-from-med-litt
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->
# Project Title
Final project for the Building AI course
## Summary
The final aim with the project is a tool that either finds or evaluates human models for describing the causes, triggers, and progression of the disease ME/CFS. 
The data for the tool is all available scientific publication related to this disease. 
## Background
After decades of research the causes, pathology, and effective treatment of the disease ME/CFS remains unknown. It is a disease that involves several bodily systems and the 
level and combination of symptoms varies much between patients. The disease can be very debilitating. The prevalence is often reported as 0.1-0.4%. 
So maybe one of every hundred in this community has a family member that is ill with this disease. 
Very often scientific papers focus responses on single systems to single stimuli whereas the answer to the mystery may well be understood first on system level. 
But, research is often made in silos, and in the specific special field of the researching writer. Yet, in (almost) each 
paper a certain cause-and-effect relation has been investigated according to well established principles, and results have been obtained, which may support statements. 
To evaluate and synthesize the information from all published literature would be a super-human effort. But, system level insights may be scattered within.

This is what motivated me to learn more about AI technology (which I'm sure has other positive effects too). And with this challenging project idea i believe I have a lot more 
to learn. Still, I am myself touched by the disease, having a family member being ill, I beleive it is possible to do, so I will not be settled until I see some results.

This is not the first idea of this kind. Some years back a data scientist from Greece use ML to identify "ME hot spots" from the literature.

Potential problems that could be solved are:
* It is rather unlikely that a researcher would take on a broad scope, evaluate an enormous amount of literature, taking an holistic perspective, 
and creating a hypothetic model for the disease. Even if one did, the task of providing the evidence for it would possibly be impossible (the rigorous 
criteria is easier to meet with narrow studies). But if someone would have an idea for a model it could maybe be possible to test it against all that is known so far.
So it would be a tool to evaluate hypothetical, or meta-models, for the disease.
* A further step would be to generate a model, based on analysis of published material, identifying relations.
* Compare assess hypotheses 

<!---Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?-->

## How is it used?
The solution would be used for research purposes.
<!-- Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)
If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">
This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]
   totPop = sum(pop)
   totFish = sum(fishers)
   # write your solution here
   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%
main()
```-->

## Data sources and AI methods
Much literature is available via open access license. Medical publications are available in databases. Some, already have AI augmented search tools as plug-ins. 
One approach would be to focus on peer-reviewed papers, which have a certain status and structure, and is probably the main contents of open databases.
Otherwise there could be relevant material in open books and other documentation.

I do not have an understanding of how a large amount of data would be handled.

I imagine the process would take place in steps, first processing data from "raw" format.
It would probably be helpful to categorize information within the data, such as what is the hypothesis, selection, method, data processing, criteria, parameters etc.
One could make an assessment of the weight, or confidence, of a result. For instance, a rigorously conducted double blind random placebo controlled study would get a 
high confidence (but maybe has a modest result) whereas an anecdotic low patient number study would have a low confidence (but maybe drastic result).
From the literature a map of the bodily systems involved in the studies needs to be created.
One would have to make a representation of one data item (paper) in some kind of model structure.
<!---Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |-->
## Challenges
<!--What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?-->
Challenges are great of course, but I would not be surprised if similar scopes have already been realised on other topics, or indeed if this very idea has already been described.
Somehow, I fail to see what would be the training and the test data here.
Scientifically, it could be that the data does not cover all aspects and domains that are relevant. If for instance life experiences, prior to disease on-set, would be significant, 
there would not be much records of that. Another problem is different terminologies, methods, and criterias in different fields. 
The tool would not produce a definitive answer, but would perhaps indicative, so that there would be some confidence in that, if the model was clinically tried, 
it would produce a valid result. 
## What next?
<!--How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? -->
I need to learn more about AI-technology, tools, and methods.
I do not think I am the first one to think about this and I am sure others have already implemented similar tools and used similar data. I need to look into that.
I am also sure there are others motivated to try to use AI to gain more insight in causes, the mechanisms of ME/CFS. 
## Acknowledgments
<!--* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc-->
The building AI course that made me take the step to get a github account and publish this.
