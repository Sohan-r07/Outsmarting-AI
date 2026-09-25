# Outsmarting-AI

This is a simple game to test your Prompt Injection skills and see if you really can outsmart a LLM model.

![Hack Club Stardance](https://img.shields.io/badge/Hack_Club-Stardance-EC3750?style=for-the-badge)

The website can be accessed here: 

https://sohan-r07.github.io/Outsmarting-AI/

**OBJECTIVE:**

The LLM has been provided with a *secret phrase* in its prompt. It is also instructed explicitly not to reveal this secret phrase to any user. 

Your objective is to use your prompt to trick or convince the LLM to give you the secret phrase or passkey that is given to it.
Try to make use of different types of roleplaying, illusions or prompt injection to support you in this.



**Features:**


**1.Local LLM:** The website runs a small 1.5B parameteer LLM model locally on your machine and hence there is no API or other cloud requirements. It also means that the website can run fully offline too!

**2.SHA256 Encryption:** The Javascript uses a SHA256 encryption to verify the Passkey so that users can not just cheat the website by using the inspect tab instead of actually trying to outsmart the LLM model. A basic but good anticheat system.

**3.Sleek Modern UI:** The website has a minimalistic sleek UI to help the users interact with the Website easily and avoid any unnecessarry bugs or issues.

**4.Zero Backend:** Uses a zero backend Client-end execution for the whole site using web-llm and WebGPU



**How to Use:**


Feel free to visit the github pages link provided with the repository to go to the website and try it out for yourself. Have a great time!



**Tips from the creator:**

You should try asking the Model for its system prompt. It is instructed to give it to you but not the secret. 
Try it out, it may work.. who knows?

Also try to trick it by asking questions like clues about the passkey or a bit of reverse psychology or some thing like
asking it if it has the correct passkey..

The model is pretty dumb as its only 1.5B parameters but should be a good starting point. Having it give you the secret is pretty easy.

The whole point is to trying and be creative and give the LLM something that it does not expect or has a straightforward answer to.
Good luck experimenting.



**Project structure:**

```bash
Outsmarting-AI
|
|--->index.html     #Handles all the HTMl and maintains the basic website layout
|--->style.css      #Contains all the CSS styling for the website.
|--->application.js #Handles the whole Website and the LLM model including the dynamic text box.
```



**Important:**

This project has been made as a part of the **HackClub Stardance** program.
This project does not promote any sort of cybercrime in relation to LLMs or otherwise. This is strictly made by me for 
**Educational Purposes** to educate people about the way bad actors could potentially misuse LLM models and AI agents that may have access to sensitive information.
This is a demonstration of how a LLM model with model sensitive data and clear instructions to not reveal it could be tricked into revealing such info.
