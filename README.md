# Factual Lie

NLTK Natural Language Tool Kit

## Project Description
Our tool is a real-time misinformation detection system designed flag false or misleading information. Using advanced Natural Language Processing (NLP) techniques, tools to analyse content, identifying potential misinformation and provides real-time alerts on the dashboard. By integrating fact-checking APIs, it cross-references flagged statements with verified databases, enhancing transparency and empowering viewers with accessible fact-checking.
The tool also includes a user-friendly dashboard that displays daily alerts with confidence scores, data sources and verification information, allowing broadcasters and journalists to make quick and informed decisions.

## Problem Statement
Due to limited tools to detect and counter false information in real time, broadcasters and viewers lack the resources needed to discern accurate information from misinformation that contributes to confusion, mistrust and the potential for widespread.
We will address the problem by providing broadcasters with an accessible, reliable tool that flags potential misinformation, allowing for immediate intervention and correction. By identifying and verifying information as it is broadcast, our tool supports the media's role as an accurate, accountable source.
________________________________________
## Target Audience
- General Public
- Government Agencies
- Broadcast Media Professionals: Journalists, Producers, and editors.
________________________________________
## Technical Approach
Our tool is built on advanced NLP, machine learning, and real-time data processing technologies to provide accurate and timely misinformation detection. Below is a breakdown of our technical approach:
1.	Flagging Potential Misinformation
o	Identifying certain keywords or entities that indicate possible misinformation
2.	ML Model:
o	Utilization of Hugging Face Fake News Models to provide analysis and confidence score
3.	Fact-Checking Integration:
o	Integrate with trusted fact-checking APIs to cross-reference flagged content with verified information in real time.
4.	Knowledge Graph Integration:
o	Build a Neo4j knowledge graph to track relationships between entities and detect patterns indicative of misinformation.
o	Use the knowledge graph to generate alerts based on contradictory claims or unverified sources.
5.	AI Agents
o	Building of AI Agents to analyse the information that was derived from the Model, API and Knowledge Graph.
6.	Real-Time Dashboard:
o	Develop an interactive dashboard using Streamlit that displays real-time alerts with confidence scores, sources, and verification details.
o	Implement matplotlib for data visualization, providing users with access to alert data.
________________________________________
## Conclusion
By delivering real-time fact-checking for live broadcasts, our tool supports media integrity, builds audience trust and encourage informed decision-making. This project will equip broadcasters with tools to maintain accountability and transparency in modern media.
## Program Flow
![image](https://github.com/user-attachments/assets/3ba7802c-0ed4-4ad8-a3f9-5af69771b2c2)

