### What is this Project all about:
-> As the name suggests, this project is about **generating musing using Deep Learning**. Two approaches are followed one is using .midi files for generating the music for that I used the LSTM model and WaveNet both but WaveNet gave better results. A piano music tone was generated in this project. For handling Music Data Music21 library was used. Code-  **music-generation-using-wavenet-and-midi-data.ipynb**. Inspiration -> https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/
<br>
On the 2nd approach, I Using the ABC Sheet music data. Which converted the whole problem statement from AI-Audio domain to NLP domain. Here also multi-layer LSTM had been used. Now the performance more improved than the waveNet model, generated music is longer and more pleasant to here. Here also the generated music is Piano tone. Code-> **Music Generation using ABC Sheet Music🎹.ipynb**. **Demo Output.mp4** is the output.
<br>
This is a project which provided more learning in NLP and AI-Audio domain.

## Project code link:
- Go to this link to visit the code - https://soumya997.github.io/Music-Generation-Using-Deep-Learning/

### **Here is the demo output video 📺**
[![Demo Output Music Lyrics Generation using Deep Learning
](https://yt-embed.herokuapp.com/embed?v=9vQPwuaiSL4)](https://youtu.be/9vQPwuaiSL4 "Demo Output Music Lyrics Generation using Deep Learning
")

### File Structure:
1. **data** -> is the data folder for  **Music Generation using ABC Sheet Music🎹.ipynb**, here I used the ABC sheet music data which is actually in .txt format. 
2. **logs** -> this is the folder which is consist of output log, that got generated while training the model.
3. **schubert** -> Is the datset folder for **music-generation-using-wavenet-and-midi-data.ipynb** which is consist of .midi files.
4. **index.html** -> is the web form of  **Music Generation using ABC Sheet Music🎹.ipynb**. The link is mentioned above.

