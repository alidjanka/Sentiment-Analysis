# Sentiment-Analysis

A web app that analyzes the sentiment of a given text, such as reviews and tells if the given text is positive or negative. Client sends the input data to AWS Lambda via REST API, AWS Lambda performs classification using the trained model stored in an Elastic File System and then sends the response back to the client. 

You can access the web app using the following link: https://alicans-sentiment-analyzer.anvil.app/

## Architecture
<p align="center">
  <img width="875" height="403" src="https://user-images.githubusercontent.com/74857138/139317023-64988b94-76b8-4075-82bb-733643793007.png">
</p>
