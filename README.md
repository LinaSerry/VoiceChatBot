# VoiceChatBot

PART 1 : CREATE KNOWLEDGE BASE
1) Navigate to https://www.qnamaker.ai/
2) Click on Create Knowledge Base
3) Click on Create a QnA service in Microsoft Azure, this will take you to the azure portal
*************** insert screenshot of azure portal and fields to fill *********************
4) step 2 screenshot 
5) Paste the following URL in Populate your KB sections : https://www.icbc.com/FAQ/Pages/default.aspx, this will parse the questions and answers
from the URL. For more information on what QNA maker can parse navigate to https://docs.microsoft.com/en-us/azure/cognitive-services/QnAMaker/concepts/data-sources-supported
********** add screenshot *****************
6) Click on create KB 
7) After that is done you are ready to publish your KB, when the KB is published take note of the http request to build your bot

PART 2: BUILD THE BOT
1) Follow the microsoft docs for a step by step guide on how to build a QnA Bot https://docs.microsoft.com/en-us/azure/cognitive-services/QnAMaker/tutorials/create-qna-bot
2) After the bot is created navigate to the build section and click on Open online code editor
3) Paste the contents of index.html into default.html file. 
4) In the Azure Portal, Go To Channel and copy the secret 
