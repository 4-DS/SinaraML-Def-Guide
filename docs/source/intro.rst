Intro
=====

**The Sinara ML Definitive Guide** is a guide to systematic development and operations of ML models using the Sinara Framework. This guide isn't about using specialized Data Science libraries to train models or math. Sinara Framework allows the Data Scientist to focus on Data Science tasks by minimize the efforts associated with engineering and other dev and ops tasks.

Perhaps we could call this a MLOps Definitive Guide on Sinara Framework. But we touch on topics beyond ML operations here, diving deep into the organization of model development and the regulations of ML dev and ops within non-IT companies

The problem of Data Science in non-IT companies 
===============================================
Why are so many companies starting to develop AI experiencing serious difficulties? If we ask such a question to the developers of AI systems, then we will get a lot of different answers, but the story as it is seen from the side of a Data Scientist is the same.

Let's imagine a large non-IT company that started to develop AI and in which data scientists appeared. Adam released the first model: passed the "weights" and a few py files to the production. 

Three months have passed and Ivan is given the task to retrain the model on the updated data. Ivan comes to Adam and asks to see how Adam trained the code. Adam finds his code, although he is not sure if this is the code he trained the model on. He tries to run it, but he does not remember how he installed the environment and in what order he launched the files. He finds some data, but he is not sure what it is. He is trying to run the code, but is not very successful. The code is too complex to figure out what went wrong on the fly. He makes a correction in one place and then everything goes wrong in another place.

As a result, Ivan is left with a broken code, some kind of data, a hint of some kind of ritual procedure that will revive the dead man. Ivan tries to restore the ritual knowledge, at which time Adam leaves the company. Then after a long and agonizing attempt Ivan comes to the conclusion that the code is wrong, the data are wrong, some of it is lost and, in general, it is easier to do everything over again.

Management is upset, why does it have to do all of the work from the beginning because of a minor change? Why is everything so long and expensive in ML? In what follows, we will refer to the sutation we have described as the Adam-Ivan problem

The solution to this problem lies in the field of engineering and organization of development and operation of ML systems. With the seeming similarity of approaches and tools with conventional software dev, ML development and operation has many of its own ML specifics. And in addition to specialized ML tools and approaches, it also requires a rethinking of established dev practices. Moreover, the use of AI in non-IT companies leads to additional challenges: we often have to solve AI tasks with fewer resources and competencies compared to IT companies. 

Sinara Framework is an essence of our years of experience (tools, guides, regulations) in organizing Data Science in non-IT companies. Sinara Framework is for those who want to focus specifically on practical Data Science, and want to minimize their efforts of related disciplines such as software and data engineering, dev and ops, infrastructure support.
   
The most important tasks for AI success?
=====================================================
What should we focus on to achieve AI success in our company? Someone answers on the data, someone will say on the correct problem statement, someone will say on the quality of Data Scientists?

All of these answers are partly correct, but they do not bring us any closer to solving the Adam and Ivan problem described above, and to understanding the organizational and engineering specifics of ML development. All of these answers are on the outer boundary of our problem, and don't allow us to grasp the essence specific to ML field.

Here are the answers that will satisfy us if we are going to solve "Adam/Ivan" problem

   The main engineering tasks of a Data Scientist:

   * Development of ML pipelines to prepare data, train, and roll out models to production
   * Systematic support (quality maintenance in changing conditions) and impovement of models through the monitoring of model performance in production, additional training and improvement of   these models via developeding of ML pipelines

   The main challenges of DS organization:
   
   * Reproducibility and transferability of ML pipelines between Data Scientists
   * Acceptable time-to-market and TCO for ML model

Such answers may seem too complicated and incomprehensible to the unprepared reader. And this is understandable. Without understanding what is ML pipeline and what is monitoring of ML models, our explanation is almost useless

To simplify, we can rephrase our answer: 

   * If we want to get more than a short-lived first version of the ML model, we need to shift our focus from ML models to ML pipelines and Model Monitoring
   * If we want to minimize TCO and time to market for our models, we need tools to cheaply develop and transfer ML pipelines and their results between Data Scientists 
   
But in any case, to be satisfied with the answer, we must take steps towards ML development practices, and understand what is ML pipeline and ML monitoring


