![Blog Picture](https://dolby.io/wp-content/uploads/2022/03/Transcribing-DolbyIO-Communications-Recordings-with-Deepgram.jpg)

# Transcribing Dolby.io Communications Recordings with Deepgram
This repository uses Dolby.io Communications REST API and Deepgram's Pre-recorded Audio API in Python.

# Overview
In [the blog](https://dolby.io/blog/transcribing-dolby-io-communications-recordings-with-deepgram/), the focus is on the importance of accessibility in conference recordings and how to automate the transcription generation process. It explores using Dolby.io Communications REST APIs along with [Deepgram](https://deepgram.com/)'s Pre-recorded Audio API in Python as an example to transcribe conference recordings to text. The aim is to provide alternative ways for people to consume the information, such as faster reading, accommodating different languages, and catering to deaf and hard of hearing people.

# Requirements
To follow along you will need: 
- A [Dolby.io Account](https://dolby.io/), this is to obtain the API Key and Secret Key
- A Deepgram account to access their Pre-recorded Audio API which requires an API Key

# Getting Started
Before we begin coding, we need to ensure we have all the proper libraries for calling these APIs. We can do this with a simple pip command (use the appropriate pip command for your operating system):

<code> pip3 install asyncio deepgram-sdk dolbyio-rest-apis </code>

This will install both the Dolby.io and Deepgram SDKs, as well as Python’s native asynchronous function library to aid us in calling the async requests the two SDKs use.

# Report a Bug 
In the case any bugs occur, report it using Github issues, and we will see to it. 

# Forking
We welcome your interest in trying to experiment with our repos. 

# Feedback 
If there are any suggestions or if you would like to deliver any positive notes, feel free to open an issue and let us know!

# Learn More
For a deeper dive, we welcome you to review the following:
 - [Communications API](https://docs.dolby.io/communications-apis/docs)
 - [Cloud-Based Audio Production Workflows with Dolby.io, Dropbox + Zapier](https://dolby.io/blog/cloud-based-audio-production-workflows-with-dolby-io-dropbox-zapier/)
 - [Beginner’s Guide to Diagnosing Audio Issues as Part of an Azure Serverless Media Workflow](https://dolby.io/blog/diagnosing-audio-issues-azure-serverless-media-workflow/)
 - [Generate a Transcript of Your Meeting](https://dolby.io/blog/generate-a-transcript-of-your-dolby-io-meeting-with-symbl-ai/)
 - [Blog Session - Communications API](https://dolby.io/blog/category/communications/)

# About Dolby.io
Using decades of Dolby's research in sight and sound technology, Dolby.io provides APIs to integrate real-time streaming, voice & video communications, and file-based media processing into your applications. [Sign up for a free account](https://dashboard.dolby.io/signup/) to get started building the next generation of immersive, interactive, and social apps.

<div align="center">
  <a href="https://dolby.io/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-0A0A0A?style=for-the-badge&logo=dolby&logoColor=white"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://docs.dolby.io/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-Docs-0A0A0A?style=for-the-badge&logoColor=white"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://dolby.io/blog/category/developer/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-Blog-0A0A0A?style=for-the-badge&logoColor=white"/></a>
</div>

<div align="center">
&nbsp; &nbsp; &nbsp;
  <a href="https://youtube.com/@dolbyio" target="_blank"><img src="https://img.shields.io/badge/YouTube-red?style=flat-square&logo=youtube&logoColor=white" alt="Dolby.io on YouTube"/></a>
&nbsp; &nbsp; &nbsp; 
  <a href="https://twitter.com/dolbyio" target="_blank"><img src="https://img.shields.io/badge/Twitter-blue?style=flat-square&logo=twitter&logoColor=white" alt="Dolby.io on Twitter"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://www.linkedin.com/company/dolbyio/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="Dolby.io on LinkedIn"/></a>
</div>




