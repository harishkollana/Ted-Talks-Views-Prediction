# Ted-Talks-Views-Prediction Proect by Harish Kollana

Okay, before going to start. Let's understand what is this Tedtalks?

TED is devoted to spreading powerful ideas on just about any topic. These datasets contain over 4,000 TED talks including transcripts in many languages. Founded in 1984 by Richard Salman as a nonprofit organization that aimed at bringing experts from the fields of Technology, Entertainment, and Design together, TED Conferences have gone on to become the Mecca of ideas from virtually all walks of life. As of 2015, TED and its sister TEDx chapters have published more than 2000 talks for free consumption by the masses and its speaker list boasts of the likes of Al Gore, Jimmy Wales, Shahrukh Khan, and Bill Gates. The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.

# Dataset Information

Number of instances: 4,005<br>
Number of attributes: 19

# Features information:
The dataset contains features like:
  talk_id: Talk identification number provided by TED<br>
  title: Title of the talk<br>
  speaker_1: First speaker in TED's speaker list<br>
  all_speakers: Speakers in the talk<br>
  occupations: Occupations of the speakers<br>
  about_speakers: Blurb about each speaker<br>
  recorded_date: Date the talk was recorded<br>
  published_date: Date the talk was published to TED.com<br>
  event: Event or medium in which the talk was given<br>
  native_lang: Language the talk was given in<br>
  available_lang: All available languages (lang_code) for a talk<br>
  comments: Count of comments<br>
  duration: Duration in seconds<br>
  topics: Related tags or topics for the talk<br>
  related_talks: Related talks (key='talk_id',value='title')<br>
  url: URL of the talk<br>
  description: Description of the talk<br>
  transcript: Full transcript of the talk
  
# Target Variable :
'views': Count of views
  
# Goal:
The goal isto build a model which predicts the views of videos uploaded on the Tedx Youtube Channel based on the past dataset i.e. given to us.
  
# Breakdown of this Notebook:
  Importing Libraries<br>
  Loading the dataset<br>
  Dataset Information<br>
  Data Analysis On Columns<br>
  Feature Engineering On Columns<br>
  Data Cleaning<br>
  Feature Selection<br>
  Fitting the models and Hyper Parameter Tuning<br>
    Linear Regressor<br>
    Random Forest Regressor<br>
    XGB Regressor<br>
  Model Comparison<br>
  Model Selection<br>
  Conclusion
