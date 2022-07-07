   
</p>
<h1 align="center"> Mobile Price Range Prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>



![Screenshot (24)](https://user-images.githubusercontent.com/102009481/177779863-376e126b-177c-4691-af6b-776c410b1f24.png)


<p>Built a Multi-Class classification model to find the relation between features of a mobile phone(RAM, Internal Memory etc) and its selling price. Model will predict the price range indicating how high the price is.</p>

<h2> :floppy_disk: Project Files Description</h2>


<p>This Project includes 2 executable files, 2 text files ,1 h5 file as well as 2 directories as follows:</p>
<h4>Executable Files:</h4>
<ul>
  
  <li><b>train.py</b> - Includes all functions required for classification operations  and generates the model.h5 file after execution.</li>
  <li><b>test.py</b> -  after execution, evaluation is done on the unseen data as in confusion_matrix.txt.</li>
</ul>

<h4>Output Files:</h4>
<ul>
  <li><b>model.h5</b> - Model contains information about the emotions of the train set, such as the Happy,Sad,Disgust,Calm and so on.</li>
  <li><b>confusion_matrix.txt</b> - Contains information about the classified emotions of the test set.</li>
  <li><b>pics</b> - which contains the output of detecting emotions through live webcam.</li>
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>train directory</b> - Includes all emotions  for the training phase of the program.</li>
  <li><b>test directory</b> - Includes all emotions for the testing phase of the program.</li>
</ul>

<h4>Files required to deploy on Heroku:</h4>
<ul>
  <li><b>Haarcascade_frontalface_alt.xml</b> -used for image processing.</li>
  <li><b>runtime.txt</b> - python environment.</li>
  <li><b>procfile</b> - Procfile is a mechanism for declaring what commands are run by your application’s dynos on the Heroku platform..</li>
  <li><b>setup.sh</b> - This file is necessary for Heroku to know which libraries it needs to run your application. .</li>
  <li><b>requirements.txt</b> - this file contains all the neccesarry dependencies .</li>
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: CNN </h2>

<p> Convolutional Neural Networks (CNNs) are a type of Neural Network that has excelled in a number of contests involving Computer Vision and Image Processing.Designing the CNN model for, emotion detection .creating blocks using Conv2D layer,Batch-Normalization, Max-Pooling2D, Dropout, Flatten, and then stacking them together and at the end-use Dense Layer for output


![1_CnNorCR4Zdq7pVchdsRGyw](https://user-images.githubusercontent.com/102009481/177744968-d0bb6264-acd9-429e-bc7e-56cd3464574c.png)



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Execution Instruction</h2>
<p>The order of execution of the program files is as follows:</p>


<p><b>1) train.py</b></p>
<p>Then, the train.py file must be executed, to define all the functions and variables required for classification operations which leads to the production of the model.h5 file. 

<p><b>2) test.py</b></p>
<p>Finally, the test.py file must be executed to evaluate the model performance on unseen data.




  Deployment Link for Heroku -Deployment Link for heroku :- https://face-recognit-apoorva.herokuapp.com/

Deployment Link for Streamlit Share - https://share.streamlit.io/apoorvakr12695/face-emotion-recognition-/main/app.py

# Run WebApp Locally

Clone the project

        git clone https://github.com/apoorvaKR12695/face-emotion-recognition-

  
Install dependencies

          pip install -r requirement.txt
  
Start local webcam

           streamlit run app.py

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Apoorva KR > | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/almabetter/mycompany/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/orgs/AlmaBetter-School/)



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p>'Facial emotion recognition methods, datasets and technologies' . [Online].</p>
      <p>Available: https://ieeexplore.ieee.org/document/9702451
  </li>
  <li><p>'Basic CNN Architecture: Explaining 5 Layers of Convolutional Neural Network.'. [Online].</p>
      <p>Available: https://www.upgrad.com/blog/basic-cnn-architecture/</p>
  </li>
  <li><p>Youtube.com, Emotion Detection using Convolutional Neural Networks and OpenCV | Keras | Realtime. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=Bb4Wvl57LIk</p>
  </li>
  <li><p>Youtube.com, 'LEARN OPENCV | Computer Vision'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=WQeoO7MI0Bs</p>
  </li>
  <li><p>Manisha-sirsat.blogspot.com, 'What is Confusion Matrix and Advanced Classification Metrics?'. [Online].</p>
      <p>Available: https://manisha-sirsat.blogspot.com/2019/04/confusion-matrix.html</p>
  </li>
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)










