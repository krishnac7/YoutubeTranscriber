# Youtube Transcriber using Watson Speech to Text

This Project is a how-to guide on creating a basic youtube transcriber web app on IBM Cloud Using Watson Speech to Text service and node-red

The Final output would look similar:

![Youtube Transcriber Demo](https://github.com/krishnac7/Media/blob/master/youtubeTranscriber/transcriberDemo.gif)

[Video Demo on Youtube](https://www.youtube.com/watch?v=tx9qjNGTZKw)

1. Login to your IBM Cloud Account
2. Goto Catalog and create a Node-red Starter App:
* [Node-Red Starter](https://console.bluemix.net/catalog/starters/node-red-starter)


![creating Services](https://github.com/krishnac7/Media/blob/master/youtubeTranscriber/CreateNode-Red.gif)

3. Once the Starter app is running, visit app URL and configure Node-red

4. Login to your node-red flows dashboard and import flow from [flows.json](https://github.com/krishnac7/YoutubeTranscriber/blob/master/flows.json)

![Importing Flows](https://github.com/krishnac7/Media/blob/master/youtubeTranscriber/ImportFlows.gif)

5. Configure Speech to Text

6. Double click on HTTP request node and enable Basic Authentication

7. Create STT Service and paste username, password in the basic authentication pallet 

### DO NOT COPY CREDENTIALS WITH QUOTES

![Create STT credentials](https://github.com/krishnac7/Media/blob/master/youtubeTranscriber/ConfigureSTT.gif)


8. Visit <app_url>/stt hit start,Allow microphone access and play the video
### Note: This demo transcribes live from the microphone so a computer with Speakers and Microphone access is needed


[Video Tutorial](https://github.com/krishnac7/Media/blob/master/youtubeTranscriber/youtubeTranscriberDemo.mp4)
