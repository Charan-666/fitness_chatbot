💪Fitness and Nutrition Chatbot


➡ every time you run the bot please make sure that you are inside the right folder and in the conda prompt go to the virtual environment where you have downloaded rasa (python framework to build bots and voice assistents). 

➡ then once you are in the right place,now to run the bot we must make sure that the rasa server is up and running ,so for that you need to type the command shown below in the prompt.

# Rasa run -m models  --enable-api  --cors  "*"
(mandatory step)

recommanded rasa version:
# 2.1.3

recommanded python  version:
# 3.8.17


Train the chatbot using Rasa:
Copy code
# rasa train
Run the chatbot in the command line interface:
Copy code
# rasa shell


✨Functionalities

Personalized workout recommendations based on user goals and fitness level.
Nutrition advice and meal suggestions tailored to dietary preferences and nutritional requirements.
Tracking user activity and progress over time.
Providing motivation and tips to help users stay on track with their fitness and nutrition goals.

✨Customization
Developers can customize the chatbot by modifying intents, entities, actions, and responses defined in the Rasa training data. Additional functionalities can be implemented by extending the chatbot's capabilities using Python code.

✨Testing
The fitness and nutrition chatbot can be tested using various user scenarios to ensure its performance and functionality meet the desired requirements. Unit testing, integration testing, and end-to-end testing can be performed to validate different aspects of the chatbot's behavior.

✨Deployment
this bot is deployed in the standalome system where i have created a bsic html file and deployed thr chatbot on the web page,where you can see that in the right bottom of your screen.