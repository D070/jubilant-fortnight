<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# verification with AI

Final project for the Building AI course

## Summary

 In official tasks , if document verification is done manually then it'll be a laborious and time consuming process . So , it can be automated using AI.


## Background
This idea can resolve the problem of time wastage . In people's daily lives there are a lot of tasks whivh require verification of certain documents. If this task is automated by feeding the system with proper training data then both time and money can be saved.
This one is a frequent problem as in most of the countries this is a basic need. In a broader view , this eases multiple tasks:
-less manpower required and people can be engaged in more productive work
-no time wastage 
-saving of paper wasted in manual document verification 
I am personally motivated to find a solution to this problem as this process has been troublesome for me too!

## How is it used?
Appropriate machines can be installed at offices where this task takes place  . Correctly filled documents can be used as training data for these machines ( or more specifically e-documents as we need to save paper too!) and just like in supervised machine learning , here too the documents eing submitted by people can be classified as correctly filled or the ones which can be 'approved' or wrongly filled that is the ones that are 'disapproved'. 
This can be brought into use in places like banks , schools , goverment offices and is really time saving technique for the employees as well as the other people who are there to get their work done. 
![![ai img](https://user-images.githubusercontent.com/114734064/194020023-5986435b-f884-4a70-a059-81c2c1e3d752.jpg)
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
```


## Data sources and AI methods
Data is self created and based on prior knowledge .
As the task is based on labelling the given document as 'correct' therefore the best method which can be used is supervised machine learning . Or for classification of documents as 'correct' and 'not correct' , classifiers using naive baiyes classifier , nearest neighbour classifier etc can be used.

## Challenges
Sometimes , during such tasks there are certain errors in documents which can't be pointed out by machines and require manual assistance . For example , if while entering certain detail , the word limit exceeds , the how to fit in the sentences using abbreviations etc can be a solution , but this can be told by a human being only . For this to me made possible by machines , the current techonology needs to be improved .
Proper assistance is required in case any document is rejected and there should be proper information about what has to be done next and currently machines can't do that.

## What next?

In order fully automate this process either more advanced AI techniques are required or a lot of training data has to be used in order to train the machine to fully guide the person for the entire proces i.e from submitting any document for verification to correcting it appropriately , so that this can become human assistance free process. 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
