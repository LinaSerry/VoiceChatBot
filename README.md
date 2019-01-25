# VoiceChatBot

PART 1 : CREATE KNOWLEDGE BASE
1) Navigate to https://www.qnamaker.ai/
2) Click on Create Knowledge Base
3) Click on Create a QnA service in Microsoft Azure, this will take you to the azure portal
4) Navigate back to the Qna maker and choose the directory ID, subscription name and azure Qna service created in step 3. 
5) Give your knowledge base a name and paste the following URL in Populate your KB sections : https://www.icbc.com/FAQ/Pages/default.aspx, this will parse the questions and answers
from the URL. For more information on what QNA maker can parse navigate to https://docs.microsoft.com/en-us/azure/cognitive-services/QnAMaker/concepts/data-sources-supported
6) Click on create KB 
7) After that is done you are ready to publish your KB, when the KB is published take note of the http request to build your bot

PART 2: BUILD THE BOT
1) Follow the microsoft docs for a step by step guide on how to build a QnA Bot https://docs.microsoft.com/en-us/azure/cognitive-services/QnAMaker/tutorials/create-qna-bot
2) After the bot is created navigate to the build section and click on Open online code editor

![alt text](https://icbclogo.blob.core.windows.net/icbc/portalCodeScreenshot.jpg)

3) Paste the contents of index.html into default.html file. 
4) In the Azure Portal, Go To Channel and copy the secret 

![alt text](https://icbclogo.blob.core.windows.net/icbc/channels.PNG)

5) Go back to the resource group where the bot was created and click on the app Service plan. In the overview section there will be a url , click on that url to navigate to your bot and append ?=SECRET COPIED IN STEP 4 to the url,  for example if your URL is https://icbcbot-8b00.azurewebsites.net you would navigate to https://icbcbot-8b00.azurewebsites.net?=SECRET
6) your bot is now ready for testing

STRETCH GOAL PART 3: INTEGRATING LUIS
1) Luis is a Language Understanding (LUIS) cloud-based API service. Get familiar with Luis https://docs.microsoft.com/en-us/azure/cognitive-services/luis/what-is-luis

2) Build a more complex bot, with several KBs, and add index.html to have the same front end experience, following this tutorial
https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/tutorials/integrate-qnamaker-luis
