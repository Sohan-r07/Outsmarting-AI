# Outsmarting-AI
This is a simple game to test your Prompt Injection skills and see if you really can outsmart a LLM model

**OBJECTIVE:**

The LLM has been provided with a *secret phrase* in its prompt. It is also instructed explicitly not to reveal this secret phrase to any user. 

Your objective is to use your prompt to trick or convince the LLM to give you the secret phrase or passkey that is given to it.
Try to make use of different types of roleplaying, illusions or prompt injection to support you in this.


**Features:**

**1.Local LLM:** The website runs a small 1.5B parameteer LLM model locally on your machine and hence there is no API or other cloud requirements. It also means that the website can run fully offline too!

**2.SHA256 Encryption:** The Javascript uses a SHA256 encryption to verify the Passkey so that users can not just cheat the website by using the inspect tab instead of actually trying to outsmart the LLM model.

**3.Sleek Modern UI:** The website has a minimalistic sleek UI to help the users interact with the Website easily and avoid any unnecessarry bugs or issues.



Project structure:
```bash
Outsmarting-AI
|
|--->index.html     #Handles all the HTMl and maintains the basic website layout
|--->style.css      #Contains all the CSS styling for the website.
|--->application.js #Handles the whole Website and the LLM model including the dynamic text box.
```
