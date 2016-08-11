# AndroidVoiceSpeakUtil
  
  @author李大帅
  
  对百度语音api的进一步简化封装，实现一行代码语音朗读指定文本
```java 
VoiceSpeakUtil vsl = new VoiceSpeakUtil(this);
//不带回调的方式
vsl.speak("这是测试语音文本");
//带回调的方式
vsl.speak("这是测试语音文本", new SpeakCallback() {

			@Override
			public void speakFinish() {
				// TODO Auto-generated method stub

			}

			@Override
			public void onError(String string) {
				// TODO Auto-generated method stub

			}
		});
