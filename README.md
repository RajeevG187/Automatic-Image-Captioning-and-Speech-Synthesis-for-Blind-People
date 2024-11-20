#Automatic-Image-Captioning-and-Speech-Synthesis-for-Blind-People

clone the repository
```
git clone https://github.com/RajeevG187/Automatic-Image-Captioning-and-Speech-Synthesis-for-Blind-People
```
Then Run the ipynb file in the sequential manner.

First the IndicTokenizer is being cloned from the VarunGumma/IndicTransToolkit.git
Loading the [blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base) to get the camtion given an image.
Loading the  "ai4bharat/indictrans2-en-indic-1B" to get translation from captions
Finally loading the gTTS to get the audio file.

Then we are creating an app.py file which is being used to deploy our projec on **ngrok**.
