# Moonshot - October progress report

October was not as productive as expected. Most of it was a continuation of the research of the datasets and how to use them efficiently.
The objective was to have the finalized data ready to train the neural network. More time will be spent next month to improve on this.
No reports were made during the period from July to September as I spent those months on a summer job, leaving me too little time to work on this project.

## Accomplishments
- Dataset selection
- Research on how to use the dataset with AI
- Testing

## Challenges
There is a lot of data to be downloaded and processed. This takes a lot of time, which is why the program runs while I do something else.

The issue is that if an issue comes up, the program will stop and after a while, the Google Colab session will be deleted along with all the data. This means that everything has to be redone from the very beginning most of the time.

A way to fix this issue would be to run the project locally and not make use of a third party. This would solve the data storage issue but might increase the runtime (my equipment is not as good as Google's). This will be investigated shortly.

Additionally, the dataset used is split into two completely different parts. One has single-instrument sounds sorted into folders while the other has sounds with multiple instruments at once, annotated with metadata. Accommodating both means doubling the code and time to write it.

## Next Steps
- Fix problem with tensorflow-io
- Check 
- Polish Functional and Technical specifications
- Do data augmentation
- Design a prototype neural network
- Train and verify (expected for December)
- Share, collect feedback and improve (long-term)