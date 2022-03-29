# Health-Web
# A health-assistance chatbot Developed using Azure Technologies
Link for the project: https://yellow-sand-001c54610.1.azurestaticapps.net/
![image](https://user-images.githubusercontent.com/67178554/160622438-5a60c811-d520-4ec2-b544-e35253d9e4b2.png =250x250)


## Main idea of the project and technologies used:
  Industry: Health

  Project Title: <br> &nbsp;&nbsp;&nbsp;&nbsp; Health-Web: A Health Assistance Chatbot

  Problem Statement/Opportunity: <br> &nbsp;&nbsp;&nbsp;&nbsp;
    People who need immediate health-related information and people having minor health symptoms often don't want to consult a doctor as it costs time and money but they need someone to talk and assist them. A Health Assistance Chatbot can help with this problem.

   Project Description:

    The project is a chatbot deployed on a website and connected to a knowledge base. People will be able to get assistance by talking to it. It will be helpful to people who need to get their health-related queries resolved. It will also assist people with small health-related problems. People will be able to educate themselves about diseases, their precautions and treatment. This will save the doctors' and patients' time in resolving small queries so that doctors can focus on patients having severe diseases.

  Primary Azure Technologies:
    Azure Bot Service, Web App Bot, QnA Maker, Static Web Apps

## Technical Details of the project:
  The project is a chatbot deployed on a website. 
  An Azure Web App Bot is used, which is powered by an Azure QnA maker, and is deployed on a website using an Azure Static Web App. <br>
  The QnA maker was trained with the following databases: <br>	&nbsp;&nbsp;&nbsp;&nbsp; COVID: <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; https://www.cdc.gov/coronavirus/2019-ncov/faq.html <br> &nbsp;&nbsp;&nbsp;&nbsp; Depression: <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; https://www.bbrfoundation.org/faq/frequently-asked-questions-about-depression
  <br> The file 'index.html' contains the HTML code for the website. The folder 'index_files' contains the files which are used by the website to display the content.
  <br> Using Github Actions, the repository is connected to an Azure Static Web App which is used to host our website. 
