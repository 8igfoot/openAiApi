# OpenAI API

A simple Google Apps Script used to call OpenAI's API with a prompt. 

Usage:

`gCoAi(prompt,200);`

Where <prompt> is the question text you want to ask OpenAI and 200 represents the max amount of tokens you want to use for this activity (200 is standard). For this to work you need a google AI account and sign up for Google Apps Scripting, both of which are free. Here is how to get started:

- [Google Apps Scripting](https://www.google.com/script/start/) - Create automations and web services
- [OpenAI API](https://openai.com/blog/openai-api) - Access AI web service API

### Example output:

`gCoAi('What is bigfoot?',null);`

Output:

>Bigfoot, also known as Sasquatch, is a legendary creature believed to roam the wilderness of North America. Descriptions of Bigfoot vary, but it is usually described as a large, ape-like creature standing between 6 to 9 feet tall and covered in hair. Many reported sightings claim it has a strong smell and emits eerie vocalizations. Despite numerous reported encounters, the existence of Bigfoot remains unproven, with most of the evidence consisting of grainy photographs, footprints, and eyewitness testimonies. The subject of Bigfoot continues to be a topic of interest and debate among enthusiasts and skeptics alike.

### Useability

|Function:|Time involved|
|---|---|
|Signup|🟩 Simple|
|API key setup|🟩 Created on opening account|
|Available code examples|🟨 Some through openAI and on web with small changes|
|Any issues|🟥 OpenAI sunset davinci, needed to use chat/completions|
