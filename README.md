Basic chat interface implemented with dialogflow as chatbot engine.

### Built with
- Java
- Dialogflow

### To integrate your own dialogflow agent in the app:
_go to app/src/main/java/com/example/chatbot/MainActivity.java_
```java
final AIConfiguration configuration = new AIConfiguration("<aceess token>", //add your own Client Access Token here
                AIConfiguration.SupportedLanguages.English,
                AIConfiguration.RecognitionEngine.System);
```
