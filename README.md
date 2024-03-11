This is just me testing out what can be done now that I have learned BPE tokenization thanks to <a href="https://www.youtube.com/watch?v=zduSFxRajkE&t=1s">this video</a>.

The poetry generated is pretty bad and mostly unorganized except there were some cases where the model maintained a poetry style and form. I set up a way to simply give a title to the generate functiion and all the technicalities to do with formatting the title in the way that the model was trained are taken care of so that the generate function is as convenient as possible.

After getting more practice with writing the tokenizer from this project, I moved on to my tiny stories project where I made the tokenizer even more simple (although it may not be as complete as those written in <a href="https://github.com/karpathy/minbpe/tree/master">minBPE</a>) but it was still able to get the job done and was much faster and easier to write.

This repository is basically closed because any developments in NLP I will make will be done in my TinyStoriesGPT repo where I outline some plans and tasks I would like to complete in that project's README. As I stated in the beginning, I did this simply to get some more practice with writing the tokenizer and to apply it in actual model training to see if the results turned out to be any better than the character level work like in <a href="https://www.youtube.com/watch?v=kCc8FmEb1nY&t=2520s">this video<a> (even though the training datasets are different I really believed that tokenization would be significant enough to fill this gap).
