# TermAI

<img src="https://i.imgur.com/8xtwQYl.png" alt="TermAI poem">

<p align="center">Start an interactive chat on your terminal using TermAI and Gemini API.</p>

<p align="center">
    <a href="https://discord.gg/tgF2ruAv7q"><b>Discord</b></a>
</p>

## Installation
A simple installation guide (Worked on Ubuntu and Debian).
* Firstly, make sure you have the latest `nodejs` and `npm` installed. 
```sh
sudo apt install nodejs
```

* Clone this repository using the script below.
```sh
git clone https://github.com/sinamathew/term-ai.git
```

* Navigate to the repo and run the installation script.
```sh   
cd term-ai 
chmod u+x install
npm install
sudo ./install
```

* Get your Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).


## Features
* Your entire chat's stored in the `"history.json"` file.

* Render code in markdown using `"markes-terminal"` module.

* To exit the chat and delete a conversation (history.json), type `"exit"` in terminal.

Feel free to create PR for update or fix issues.
