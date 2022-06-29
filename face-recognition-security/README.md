# Door Security System with Facial Recognition

![gif](https://i.imgur.com/ZgfokcZ.gif)

This programme processes frames from live video and compares detected faces against a set of known face encodings. 

If there is a match, the person is considered to be known and nothing is done. 
If there is no match found, the person is considered to be an intruder and an email is sent with an image of the intruder by invoking a shell script.

I used Adam Geitgey's face recognition API. For more details, see his [Github repo](https://github.com/ageitgey/face_recognition)
