
<h1> 💪 FitFusion AI 💪 </h1>

###### This project was made for [Los Altos Hacks VII](https://losaltoshacks7.devpost.com/ "Los Altos Hacks VII"), the largest high school hackathon in the world (425 participants), in less than 24 hours and won [3rd place](https://devpost.com/software/fitfusion-ai "FitFusion AI on DevPost").

## 📝 Overview 📝
FitFusion AI is an AI-powered fitness project that offers a personalized workout schedule and plan based on your characteristics. To enhance each workout, it provides a tracker that uses computer vision to ensure proper form and keeps a record of your workout results so you can track your progress over time. It also includes a personalized AI trainer to answer your fitness questions. Achieve your fitness goals with our cutting-edge technology.

## 🎯 Initiative 🎯

[**Google Slides**](https://docs.google.com/presentation/d/1OXqh9sOShfV5hX5ayfGW8IWrVRSj2gcLwSxL_Wa3PYU/edit?usp=sharing)

## 🎬 Demo 🎬 


https://user-images.githubusercontent.com/103217739/231323008-a9564b20-c10c-4e42-be3b-b3cc7d2495be.mov



## ⚙️ How it Works ⚙️
FitFusion AI is an innovative fitness project that utilizes advanced AI and computer vision technology to help you achieve your fitness goals. The project comprises three main components: personalized workout plan, rep tracker, and personalized fitness trainer.

To create a personalized workout plan, our AI algorithm analyzes a combination of your inputted characteristics, such as weight, height, fitness level, and workout goals. Based on this analysis, the algorithm generates a customized workout plan tailored to your specific needs.

Once you select the workout you want to do, you can move onto our rep tracker. Our rep tracker utilizes OpenCV and MediaPipe Pose Landmark Estimation to track multiple body parts and analyze various distances and angles in three dimensions to ensure that you perform each rep with proper form. After each workout, the number of completed reps is stored and can be viewed in a graph displaying your progress over time.

Lastly, we include a personalized fitness trainer is powered by a customized version of GPT3.5-Turbo that is fine-tuned to provide expert advice on any fitness-related questions you may still have. Whether you need guidance on exercise techniques, nutrition, or workout routines, our AI trainer is there to help.

With our cutting-edge technology and personalized approach to fitness, FitFusion AI is the perfect tool to help you achieve your fitness goals.

## 🚀 Usage 🚀
<p> To run this project on your own you must do the following steps 
<br></br>
  <b>1.</b> Navigate to a command line and clone the repository 
</p>

```
git clone https://github.com/butter-my-toast/la-hacks/ 
```
<p>
  <b>2.</b> Install the dependencies
</p>

```
pip install -r requirements.txt
```

  <b>3.</b> Then retrieve an API key from [OpenAI](https://platform.openai.com/account/api-keys "OpenAI") \
  You will need to update the string in `api_key.py` to match your API key
</p>
<p>
  <b>4.</b> Finally, you can run the application!
</p>

```
python gui.py
```

## 🛠️ Technologies used 🛠️
  Computer Vision: <b>[OpenCV](https://github.com/opencv/opencv/blob/4.x/LICENSE)</b> \
  Infrastructure for computer vision application 
  
  Pose Estimation: <b>[MediaPipe](https://github.com/google/mediapipe/blob/master/LICENSE)</b> \
  Used to get the specific landmarks on a human body 
  
  NLP Model: <b>[OpenAI's GPT3.5-Turbo](https://openai.com/product)</b> \
  Used for planning workouts and as a personal trainer 
  
  GIF Reader: <b>[imageio](https://github.com/imageio/imageio/blob/master/LICENSE)</b> \
  Used to convert GIFs into a list of images  
  
  Linear Algebra Computation: <b>[numpy](https://github.com/numpy/numpy/blob/main/LICENSE.txt)</b> \
  Used to perform linear algebra computations behind the scenes for machine learning models and for our rep checker 
  
  Frontend: <b>[Tkinter](https://github.com/PacktPublishing/Python-GUI-Programming-with-Tkinter/blob/master/LICENSE)</b> \
  Used for our frontend framework 
  
  Graphing: <b>[matplotlib](https://github.com/matplotlib/matplotlib/blob/main/LICENSE/LICENSE)</b> \
  Used to graph the workout progress
  

## 🧑‍💻 Authors 🧑‍💻
Alexander S. Du / [@Mantlemoose](https://github.com/Mantlemoose "Mantlemoose's github page") \
Prarthan Ghosh / [@coder2003lucky](https://github.com/coder2003lucky "coder2003lucky's github page") \
Eashan Chatterjee / [@EashanC23](https://github.com/EashanC23 "EashanC23's github page") \
Nicholas Kann / [@nick-kann](https://github.com/nick-kann "nick-kann's github page")
