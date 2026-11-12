मोबाइल से APK बनाने का तरीका (GitHub Actions)

1. GitHub पर साइन इन करें और New repository बनाएं। नाम: Rajesh-Motivation-Video-Story
2. Repository को Public या Private रख सकते हैं। Create repository दबाएं।
3. इस ZIP को फोन में Extract करें। Extract हुए RajeshMotivationAndroid फ़ोल्डर के अंदर की सभी फ़ाइलें और फ़ोल्डर repository के root में Upload files से अपलोड करें। ZIP फ़ाइल को सीधे अपलोड न करें।
4. Upload के बाद Actions टैब खोलें। पहली बार workflow enable करने के लिए पूछा जाए तो Enable दबाएं।
5. Build Android APK workflow चुनें और Run workflow दबाएं।
6. Build पूरा होने पर workflow run खोलें। नीचे Artifacts में Rajesh-Motivation-debug-apk डाउनलोड करें। ZIP को Extract करें; उसमें app-debug.apk मिलेगा।
7. APK खोलकर Install करें। Android पूछे तो इस स्रोत से Install की अनुमति दें। केवल अपनी बनाई हुई APK इंस्टॉल करें।

ध्यान दें: यह debug APK है। पहली बार build में कुछ मिनट लग सकते हैं। Build fail होने पर Actions में लाल error का screenshot भेजें।
