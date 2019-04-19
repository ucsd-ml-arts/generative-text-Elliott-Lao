# Project 1 Generative Text

Elliott Lao, eylao@ucsd.edu

## Abstract

Project 1: Text Generation [Simulated Sir David Attenborough] \n
The concept of this project was to create a pseudo Sir David Attenborough. Given his prolific work as a natural historian and broadcaster, I thought it would be appropriate to represent it in the form of a nature documentary. The documentary has been rendered in script form, provided by the RNN, and manually chosen images to accompany it. For the technical implementation of the project, I used the Beautiful Soup library to extract scripts of David Attenborough’s works off of “Springfield! Springfields”’s database and assemble my training data. The character-based RNN used was a slightly modified version of the example given in class, with the most notable differences being two additional RNN layers. The model was trained for 45 epochs and text generated using a temperature value 0.6; using any higher temperature value leads to generating nonsensical “words”. Scripts generated by the system have the correct form and structure of the scripts used for training, even capturing captioned sounds. However, most sentences fail to actually make sense or keep to a singular subject matter.     


## Files

Briefly decribe the files that are included with your repository:
- corpus.txt - training data collected using Beautiful Soup
- scraping.ipynb - code for acquriing training dataset
- Text_Generation.ipynb - my code for both training the model and generating an output

## Results

- My results and a copy of the abstract can be found under Project 1_ Text Generation [Simulated David Attenborough].pdf.

## Notes

Any implementation details or notes on repeating your work. 

The included notebooks should run on datahub without needing to install any additonal packages or libraries. 

## Reference

Project requirements: [doc](https://docs.google.com/document/d/13ueceIyuUc4ATD7B-SFZK641MycFZ57eZ9n1lQ3Y1CM/edit?usp=sharing)
