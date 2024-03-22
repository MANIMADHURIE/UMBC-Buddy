# UMBC Buddy -A Chatbot for UMBC International Students using Dialogflow

## Abstract:
International students face a unique set of challenges when adjusting to life in a new country and pursuing their academic goals. Navigating unfamiliar cultural norms, academic systems, and campus resources can be overwhelming. To address these challenges, we developed an intelligent chatbot using Dialogflow, a natural language processing (NLP) platform, to provide comprehensive support to international students at the University of Maryland, Baltimore County (UMBC). The chatbot leverages the power of OpenAI’s search algorithms to accurately answer user queries related to UMBC, ranging from admissions procedures to student life. A webhook seamlessly integrates Dialogflow with a backend Python script, enabling the chatbot to access and provide real-time information to the students. Additionally, we integrated the chatbot with Slack, a popular messaging platform, allowing students to interact with the chatbot directly within their preferred communication channel.

![image](https://github.com/MANIMADHURIE/UMBC-Buddy/assets/37103568/b2afbf53-96f9-4631-890e-3e2233d4d16f)

## Technologies Used:

We have used the following technologies to develop the UMBC Buddy:

 1) Google Dialogflow
 
 2) Open AI
 
 3) Ngrok
 
 4) Slack

## Methodology:

Chatbot was tailored for UMBC international students, enhancing their experience and support. The official International Student Arrival Guide, sourced from UMBC, served as the primary text corpus for this work, which provided valuable information about admission, arrival details, classes, and services.

Our methodology involved several key steps:

• **Intent Recognition**: Categorized various student inquiries into specific intents to better understand and address their concerns effectively.

• **Entity Recognition**: The chatbot was trained to identify and extract relevant information from user queries, enabling it to provide accurate responses.

• **Knowledge Base Construction**: Compiled a structured repository of UMBC-related information to serve as a foundation for the chatbot's responses.

• **Dialogflow Integration**: Utilized Dialogflow, a natural language understanding platform, to build the chatbot's conversational interface. This involved defining intents, entities, and orchestrating the conversational flow.

• **OpenAI Integration**: By integrating OpenAI's advanced search algorithms, enhanced the chatbot's ability to provide precise and comprehensive responses to user inquiries.

• **Ngrok and Webhook Integration**: Used Ngrok to expose our locally hosted backend code to the internet, allowing Dialogflow to communicate with it via a webhook. This facilitated real-time data transmission between the chatbot and our backend Python script.

## Integration with Slack:

To extend the accessibility of our chatbot to a broader user base, we integrated it seamlessly with the Slack application using Webhook functionality. Users can conveniently access the chatbot by simply downloading the Slack application on their computers or mobile devices. This integration offers users the ability to interact with the chatbot effortlessly with just a single click.
When users input their queries within the Slack application, the system redirects these queries to Dialogflow through the Webhook integration. Subsequently, Dialogflow processes these queries and efficiently delivers the corresponding responses back to the users. This robust integration ensures a
smooth and user-friendly experience, allowing individuals to interact with the chatbot seamlessly within the familiar Slack environment.

**Result for query regarding international grocery stores:** 

![image](https://github.com/MANIMADHURIE/UMBC-Buddy/assets/37103568/944ecec3-f4b4-4692-8e61-bc35cd026084)

## FUTURE ENHANCEMENTS:

This chatbot integration extends beyond its initial scope and can be synergized with the UMBC transit system, thereby offering students real-time updates regarding transit schedules and routes. Additionally, integration with the UMBC International Student and Scholar Services (ISSS) system can enable the tracking of crucial application statuses such as I-20 and Curricular Practical Training (CPT) applications.
Furthermore, this chatbot’s functionality can be expanded to encompass the dissemination of emergency alerts across the campus. This enhanced capability ensures timely and crucial notifications reach students promptly, contributing to campus safety and security measures.

## CONCLUSION:

The integration of this Dialogflow-based chatbot marks a significant transformation in bolstering support for international students at UMBC. Through its provision of personalized assistance available around the clock, this chatbot is set to substantially enhance accessibility, operational efficiency, and the overall student journey. As we persist in refining and broadening its functionalities, we foresee this chatbot evolving into an indispensable asset, not only for international students at UMBC but also for all students. This strategic evolution positions the chatbot as an instrumental tool, promising continuous improvement in student support services and experiences.













