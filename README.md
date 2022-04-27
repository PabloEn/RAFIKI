# RAFIKI
my bot on kommunicate.io(https://www.kommunicate.io/livechat-demo?appId=f101c515c9d39eb58db82cd4add263d2&botIds=rafiki-agent-a2dxi&assignee=rafiki-agent-a2dxi)
school project Rafiki bot
1. Install a virtual environment by runnning the following
```
virtualenv chatbotenv
source chatbotenv/bin/activate
```

2. Install all the required libraries 
```
pip install nltk
pip install numpy
pip install keras
pip install tensorflow
pip install flask
```

Run the chatbot.py file to create the model
```
python chatbot.py
```

Run the APP to create a Flask front end on port 8888 (or any port the app is pointing to)
```
python app.py
