# Rajesh Motivation Video & Story — Android Starter v1.1

## शामिल सुविधाएँ
- हिंदी मोटिवेशनल होम स्क्रीन और विचार
- तीन नमूना हिंदी कहानियाँ
- कहानी विस्तार से पढ़ना
- Android Text-to-Speech से कहानी सुनना (फोन में Hindi voice data उपलब्ध होना चाहिए)
- अपनी कहानी लिखना और Android Share Sheet से साझा करना
- फोन से वीडियो चुनना और ऐप में चलाना (Media3 player)

## अभी शामिल नहीं
- कहानी से स्वचालित AI वीडियो/MP4 निर्माण
- क्लाउड AI voice (यह संस्करण फोन की built-in TTS आवाज़ उपयोग करता है)
- ऑनलाइन अकाउंट, सर्वर, क्लाउड बैकअप या ऐप स्टोर प्रकाशन

इन ऑनलाइन सुविधाओं के लिए चुने हुए AI/video provider की API, सुरक्षित backend और credentials चाहिए। API secret को Android ऐप में सीधे रखना सुरक्षित नहीं है।

## Android Studio में चलाएँ
1. ZIP Extract करें।
2. Android Studio में `Open` चुनें और `RajeshMotivationAndroid` फ़ोल्डर खोलें।
3. Gradle Sync पूरा होने दें।
4. फोन में Developer Options और USB Debugging चालू करें या emulator चुनें।
5. Run दबाएँ।

## APK बनाना
Android Studio: Build > Build Bundle(s) / APK(s) > Build APK(s).
यह ZIP Android source project है, तैयार APK नहीं। इस वातावरण में Android SDK/Gradle build उपलब्ध नहीं था, इसलिए APK compile/test नहीं किया गया।
