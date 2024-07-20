# TermAI

<img src="https://ik.imagekit.io/unburn/gcc.svg">

<p align="center">Start an interactive chat on your terminal using TermAI and Gemini API.</p>

<p align="center">
    <a href="https://discord.gg/tgF2ruAv7q"><b>Discord</b></a>
</p>

## Installation
A simple installation guide.
* Firstly, navigate to [Google AI Studio](https://aistudio.google.com/app/apikey) to get a Gemini API key.

* Clone this repository using the script below.
```sh
git clone https://github.com/sinamathew/term-ai.git
```

* Navigate to the repo and run the installation script.
```sh   
cd term-ai 
chmod u+x install
sudo ./install
```

## Configuration
First of all, get your API key from https://aistudio.google.com/app/ and paste it in the index.js file.

```javascript
const API_KEY = "YOUR_API_KEY";
```

Install the required package by running:
```
npm install
```

All is done, to start the chat run:
```
term-ai 
```

## Features
Your entire chat's stored in the `"history.json"` file.

To exit the chat and delete a conversation (history.json), type `"exit"` in terminal.
