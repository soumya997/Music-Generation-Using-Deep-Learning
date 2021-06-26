# Music Generation Using Deep-Learning 🎵🎶
### What is this Project all about🤔:
As the name suggests, this project is about **generating musing using Deep Learning**. Two approaches were used.  One is using .midi files for generating the music for that I used the LSTM model and WaveNet both but WaveNet gave better results. A piano music tone was generated in this project. For handling Music Data Music21 library was used. Code-  **music-generation-using-wavenet-and-midi-data.ipynb**. Inspiration -> https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/
<br><br>


On the 2nd approach, I used the ABC Sheet music data with LSTM. Which converted the whole problem statement from AI-Audio domain to NLP domain. Here multi-layer LSTM had been used. Now the performance more improved than the waveNet model, generated music is longer and more pleasant to here. Here also the generated music is Piano tone. Code-> **Music Generation using ABC Sheet Music🎹.ipynb**. **Demo Output.mp4** is the output. Used this website(https://www.abcjs.net/abcjs-editor.html) to convert outputed abc sheet music to real music.
<br>
This is a project which provided more learning in NLP and AI-Audio domain.


### **Here is the demo outputs 📺**
[![Watch the video](https://img.youtube.com/vi/KB00Bb9eRLk/maxresdefault.jpg)](https://youtu.be/KB00Bb9eRLk)
<br>
<br>
[![Watch the video](https://img.youtube.com/vi/9vQPwuaiSL4/maxresdefault.jpg)](https://youtu.be/9vQPwuaiSL4)
<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/KB00Bb9eRLk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Charecters used mostly in the inputed ABC sheet musics📊:**

<br>
<br>
<div style="text-align:center"><img src="https://i.imgur.com/Jj1GOtq.png" /></div>

#### Model Architecture of the model that had been used in the ABC Sheet data📊:

<br>
<br>
<div style="text-align:center"><img src="https://i.imgur.com/wGKTpvp.png" /></div>

<br>

### File Structure:
1. **data** -> is the data folder for  **Music Generation using ABC Sheet Music🎹.ipynb**, here I used the ABC sheet music data which is actually in .txt format. 
2. **logs** -> this is the folder which is consist of output log, that got generated while training the model.
3. **schubert** -> Is the datset folder for **music-generation-using-wavenet-and-midi-data.ipynb** which is consist of .midi files.
4. **index.html** -> is the web form of  **Music Generation using ABC Sheet Music🎹.ipynb**. The link is mentioned above.
<br>

**Packages Required to Build the Project:**

- **Numpy**- number python library
- **pandas,RegEx** - data handling library
- **Tensorflow 2.0** - Deep Learning Library
- **Music21** - For handeling midi files
- **Matplotlib,Seaborn, Plotly, Bokeh** - Visualization purpose
- **json,os** -utility packages

**Please star🌟 this repo if you like it. It motivates me to produce more quality projects :)**
