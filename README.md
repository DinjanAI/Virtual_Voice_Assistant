# Virtual_Voice_Assistant

Welcome to Virtual Voice Assistant, your go-to virtual assistant for a wide range of tasks. Whether you need to stay informed, entertained, or productive, Virtual Voice Assistant has got you covered. Powered by machine learning and natural language processing, interacting with your computer has never been easier – simply speak and let Virtual Voice Assistant handle the rest!

## Features
Virtual Voice Assistant comes loaded with a plethora of features to enhance your computing experience, including:

- Jokes: Bring a smile to your face with hilarious jokes.
- News: Stay informed with the latest headlines.
- IP Address: Quickly find out your IP address.
- Entertainment: Stay up-to-date with the latest movies and TV series.
- Weather: Get current weather updates for any city.
- Internet Speed: Test your internet speed with ease.
- System Stats: Monitor your system's performance.
- Image Generation: Generate images from text inputs.
- Emails: Send emails to friends and colleagues effortlessly.
- System Operations: Perform various system operations seamlessly.
- Screenshots: Capture important moments with ease.
- Brief Information: Get concise information on any topic or personality.
- Math Operations: Solve math problems quickly.
- App and Website Launch: Open your favorite apps and websites effortlessly.
- Notes: Take notes and stay organized.
- Chat History: Save and refer back to your chat history.
- Google Search: Find information online instantly.
- YouTube Playback: Enjoy your favorite songs and videos on YouTube.
- Maps: Access maps and calculate distances between locations.
- 
Note: To enable email functionality, ensure that the "Less secure apps" option is enabled in your Gmail account settings.

API Keys
To run this program, you'll need several API keys. Register for your API keys by clicking on the following links:

- [OpenWeatherMap API](https://openweathermap.org/api)
- [WolframAlph API](https://products.wolframalpha.com/api)
- [News API](https://newsapi.org/)
- [TMDB API](https://developer.themoviedb.org/docs/getting-started)
- [DreamStudio API](https://platform.stability.ai/docs/getting-started/authentication)


Installation
Before installing, ensure that `Python` and `pip` are installed on your system.

Clone the repository:

```bash
  git clone https://github.com/YourUsername/Virtual-Voice-Assistant.git
```
Navigate to the project directory:

```bash
  cd Virtual-Voice-Assistant
```
Open the `.env` file in the Data directory and insert your API keys.

Run the setup script:

```bash
  python setup.py
```
Navigate to the Plugins directory:

```bash
  cd Plugins
```
Start the virtual voice assistant:

```bash
  python main.py
```
You're all set! Virtual Voice Assistant should now be up and running on your system.

## Code Structure
```bash
├── Virtual-Voice-Assistant
    ├── Data
        ├── .env
        ├── chat_model
        ├── chats.db
        ├── intents.json
        ├── label_encoder.pickle
        └── tokenizer.pickle
    ├── Plugins
        ├── API_functionalities.py
        ├── browsing_functionalities.py
        ├── database.py
        ├── gmail.py
        ├── image_generation.py
        ├── main.py
        ├── model_training.py
        ├── system_operations.py
        └── websites.py
    ├── requirements.txt
    └── setup.py
```
