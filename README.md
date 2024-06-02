# ToxiCheck
### A tool to safeguard developer forums from cyberbullying with real-time toxicity detection

## About

ToxiCheck is a Google Chrome extension designed to detect cyberbullying and offer toxicity reports on comments, primarily on software developer websites such as GitHub. Additionally, ToxiCheck helps users avoid toxic language by suggesting gentler alternatives as they type.

[Demo Video](https://youtu.be/wdOJUzeFAxo)

## Technical Details

Models used:
1. Toxic-BERT [[1]](https://huggingface.co/unitary/toxic-bert)
2. BART-base-detox [[1]](https://aclanthology.org/2022.acl-long.469.pdf) [[2]](https://huggingface.co/s-nlp/bart-base-detox)

UI:
1. Vanilla JS
2. Chart JS

## Flow Diagrams
Working of the Bullying Classifier (Text Blurring Mechanism)

![image](https://raw.githubusercontent.com/SachinSahu431/ToxiCheck/main/images/1.png)

Working of the Autosuggestor (Suggestion Mechanism)

![image](https://raw.githubusercontent.com/SachinSahu431/ToxiCheck/main/images/2.png)

## Major Features

### Toxicity Chart

![image](https://user-images.githubusercontent.com/80470843/235318719-f7dc54db-7e00-4299-84f6-009baf142f49.gif)

### Autosuggestor feature

![image](https://user-images.githubusercontent.com/80470843/235319414-18d4ea10-7bc9-49c4-afd2-dedfb30ee764.gif)

## Features for Github

### Toxicity charts for Github

![image](https://user-images.githubusercontent.com/80470843/235321248-55b7b9c5-df7a-47a7-9fc5-f82a52de2efb.png)

### Autosuggestor for Github

![image](https://user-images.githubusercontent.com/80470843/235321099-488ea1d0-5733-49ba-8797-696838492b6e.png)

## Instructions
1. Clone the repository
2. Enter the directory Toxicheck and type 
```
$ npm install
```
3. Edit the bearer token inside the ``app.js` file with your huggingface (write-enabled) token.
4. In Chrome browser, type:
```
chrome://extensions/
```
5. Click on "Load Unpacked" option and browse to the Toxicheck folder, then select it.
6. Enable/Reload the extension
7. Navigate to the websites you wish to monitor.

## Meet the Team
1. Harmit Singh
2. Anush Mangal
3. Soham Nandy
4. Sachin Sahu
