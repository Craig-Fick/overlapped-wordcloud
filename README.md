# overlapped-wordcloud
Useful for blending the word cloud shape over the original image


Here is an example of the first time I used this code.

https://www.reddit.com/r/dataisbeautiful/comments/oy9k65/word_cloud_of_i_have_a_dream_oc/

The original image I used to put the word cloud shape over.

https://www.studentnewsdaily.com/wp-content/uploads/2015/01/mlk-590x295.jpg

I then created a .txt file of the speech I found online here.

https://www.huffpost.com/entry/i-have-a-dream-speech-text_n_809993


You should know:
To create a word cloud in a specific shape, the shape you want it in has to be in a color other than white. The area around the shape has to be fully white. I edited the photo using paint to capture MLK from the picture and eliminate any background colors so it is all white.

The steps you take to make this are fairly simple. If you are using jupyter notebook you want to upload your picture and .txt file right into your jupyter folder where you are creating the project. This makes it easier than typing in the location of the file on your computer. 

I named the picture sil2.jpg.      # short for silhouette
I named the .txt file dream.txt.

The first part you will create a wordcloud in the shape of the image. It will then save this image in the same folder as the project in Jupyter Notebook under the name wordCloud.png.

The second step of the code is blending the original MLK image with the wordcloud overtop. After blending, the file will be saved in your Jupyter folder under the name blended.png.



