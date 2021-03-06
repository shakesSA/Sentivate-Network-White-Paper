
# सेंटिवटे नेटवर्क वाइट पेपर

![Logo](https://sentivate.com/wp-content/uploads/brizy/3443/assets/images/iW=269&iH=274&oX=0&oY=0&cW=269&cH=274/SNTVTbig.png)

##### शीर्षक: सेंटिवटे - द यूनिवर्सल वेब।
#####  संक्षेप
सेंटिवटे एक उच्च स्तरीय वेब है (केंद्रीकृत केंद्रित लेकिन विकेंद्रीकृत घटकों द्वारा बढ़ाया गया) आधुनिक वेब के लिए एक व्यवहार्य और वास्तववादी प्रतिस्थापन बनने के लिए। क्षमताओं से आगे जाने के लिए नेटवर्क को बनाया गया है जो केवल केंद्रीयकृत या विकेंद्रीकृत नेटवर्क ही पेश कर सकते हैं। सेंटिवटे सीधे निम्नलिखित मुद्दों को संबोधित करता है : बैंडविड्थ संकट, पुराने प्रोटोकॉल, टूटे हुए डी एन एस, जवाबदेही की कमी, पहचान की कमी, प्रतिक्रियात्मक सुरक्षा, डोमेन नियम और वेब वर्गीकरण।

##### ध्यान केंद्रित
यह वाइट पेपर मुख्य नेटवर्क डिज़ाइन पर केंद्रित है जो विएट, एच अप्प्स और यूनिवर्सल वेब के लिए बेस नेटवर्क और घटकों के रूप में कार्य करता है। एक अतिरिक्त वाइट पेपर पूरी तरह से विएट पर जारी किया जाएगा। 

## प्रस्तावना
##### वर्ल्ड वाइड वेब की स्थिति

वर्तमान में, वैश्विक स्तर पर हम अपने आप को एक दूसरे से जुड़े हुए संचार के विनाशकारी माध्यम का उपयोग करना जारी रखे हुवे हैं। मानवता की मांग तेजी से बढ़ रही है जिसे वर्ल्ड वाइड वेब पूरा नहीं कर सकता है। जैसे-जैसे हम बढ़ते हैं, विकसित होते हैं, और सौर मंडल से परे जोखिम उठाना, हमारा आत्यावश्यक कार्य उस प्रौद्योगिकी में क्रांति ला देता है जिसपर हम निर्भर करते हैं।

वर्ल्ड वाइड वेब की वर्तमान स्थिति बहुत लापरवाह है। यदि मानवता मौजूदा मंकी-पैच समस्याओं को जारी रखती है, तो इंटरनेट "वाइल्ड वाइल्ड वेस्ट" बना रहेगा। मानवता की लगातार बढ़ती मांगों को वेब की वर्तमान स्थिति से कभी पूरा नहीं किया जा सकता। हमें क्रांतिकारी विषयों में सोचना शुरू करना चाहिए न कि विकासवाद-संबंधी। इसका समाधान समकालीन प्रणालियों, ब्राउज़रों, भाषाओं, प्रोटोकॉल, और प्लेटफार्मों के साथ बढ़ी हुई सुरक्षा, गति, निपुणता, जवाबदेही, विश्वास, पहचान, क्षमता और विश्वसनीयता का पूर्ण प्रतिस्थापन है। सूचना के नए युग में परिवर्तित होने के लिए हमें उस चीज़ को बदलना होगा, जिसके साथ हम बहुत सहज हो गए हैं।


###### बैंडविड्थ संकट
[बैंडविड्थ संकट](https://www.scientificamerican.com/article/the-bandwidth-bottleneck-that-is-throttling-the-internet/) इस मुद्दे को हल करने के लिए हमें आधुनिक क्रांतिकारी तकनीक की आवश्यकता है मौजूदा घटकों को बदलने के लिए। यदि हम नहीं करते हैं, तो फ़ास्ट लेन्स और डेटा की प्राथमिकताकरण हमारा एकमात्र विकल्प है। वह सभी डर जो लोगों को है नेट न्यूट्रैलिटी को भंग करना वेब स्पिनिंग पर हमारी एकमात्र उम्मीद होगी । IoT की अवश्यंभावी वृद्धि, प्रति व्यक्ति अधिक डिवाइस, प्रति घर अधिक डिवाइस, स्व-चलित कार, कार बीमा विश्लेषिकी, और विकासशील देश जो ऑनलाइन आ रहे हैं बैंडविड्थ सोख लेती हैं जो हमारे पास नहीं हैं।

###### पुरानी वेब जिस पर हम भरोसा करते हैं वह खुद को खा रही है
HTTP और DNS को बहुत समय पहले बनाया गया था आधुनिक मांगों को ध्यान में रखे बिना। अधिक से अधिक बैंडविड्थ सोख लिया   जा रहा है, HTTP अपने लंबे मापनीयता मुद्दों को दिखाना जारी रखा है, और DNS भरोसेमंद या मापनीय नहीं है। यदि वेब के आधे DoS-ing विशिष्ट DNS सर्वर से बंद हो सकते हैं तो इसमे स्पष्ट शिल्पविद्या-संबंधी समस्या है। HTTP वर्तमान वाहन है पैसे के लिए । संपूर्ण डिजिटल अर्थव्यवस्था को HTTP द्वारा पहुंचाया जाता है। HTTP या DNS को धीमा करने का मतलब है, वैश्विक अर्थव्यवस्था में भारी गिरावट। DNS और HTTP स्वाभाविक रूप से टूट गए हैं, खराब मापनीयता है, अत्यंत धीमी गति से , आधुनिक सुविधाओं की कमी है, बैंडविड्थ खाते हैं, और उपभोक्ताओं और व्यवसायों के अरबों नुकसान होते हैं। यदि हम इस मुद्दे को हल नहीं करते हैं, तो हम अर्थव्यवस्था के बड़े झटके का अनुभव करेंगे। जब आप सभी डॉलर संकेतों में कारक होते हैं तो जल्द ही पता चलता है कि एक धीमा वेब एक वैश्विक मानवीय संकट है।

1.  [एक सेकंड की देरी अमेज़ॅन की बिक्री मे 1.6BB का नुकसान हो सकता है।](https://www.fastcompany.com/1825005/how-one-second-could-cost-amazon-16-billion-sales)
2.  [_“10 साल पहले, अमेज़ॅन ने पाया कि प्रत्येक 100 मिलीसेकंड विलंबता ने उनका बिक्री में 1% नुकसान किया”_](https://www.gigaspaces.com/blog/amazon-found-every-100ms-of-latency-cost-them-1-in-sales/)
3.  [_“10 साल बाद, 2017 अकामाई अध्ययन से पता चलता है कि वेबसाइट लोड में प्रत्येक 100-मिलीसेकंड की देरी रूपांतरण दरों को 7% तक चोट पहुंचा सकती है - जो कि बिक्री में - 6% -कि महत्वपूर्ण गिरावट है जब अमेज़ॅन ने पहली बार विलंबता के बारे सेकंड और मिलीसेकंड में बात की। यह दर्शाता है कि ऑनलाइन विक्रेताओं के लिए चीजें आसान नहीं हैं क्योंकि उपयोगकर्ता का अनुभव ई-कॉमर्स सफलता के लिए महत्वपूर्ण होता जा रहा है।”_](https://www.akamai.com/us/en/about/news/press/2017-press/akamai-releases-spring-2017-state-of-online-retail-performance-report.jsp)

###### विकेन्द्रीकृत वेब उर्फ वेब 3.0 असफल है
हम जानते हैं कि वैश्विक अर्थव्यवस्था को एक प्रदर्शनकारी और सस्ती वेब की आवश्यकता होती है। यदि पूरी तरह से विकेंद्रीकृत वेब ने आधुनिक वेब को बदल दिया, तो यह बैंडविड्थ संकट को तेज करेगा और हमें एक डायस्टोपियन वेब पर लाएगा। वेब 3.0 एक जादू की दुनिया, एक क्रांतिकारी विचार या एक समाधान नहीं है; यह एक पैसा कमाने का तरीका है। व्यापार नैनोसेकंड्स में हो रहे हैं वैश्विक अर्थव्यवस्था के पास जांच करने और फिर नेटवर्क के माध्यम से प्रचार के लिए सेकंड या मिनट का समय नहीं है। उपभोक्ताओं के लिए वेब की प्रतिस्थापन धीमी और अधिक महंगी नहीं होनी चाहिए। वेब 3.0 की लागत अधिक है और वे चीजों को छुपाना पसंद करते हैं जैसे कि यह सभी ऑन-चेन है और एक ऐप प्रारंभ करने के लिए बहुत कम लागत लगती है। वास्तविकता यह है कि, आपको वह मिलता है जिसके लिए आप भुगतान करते हैं। वेब 3.0 उपयोगकर्ताओं के सेवाओं के बजाय ऑफ़सेट खर्च हैं , जिसके परिणामस्वरूप खराब सेवा भी होती है। एक अन्य आम तर्क है कि उपयोगकर्ताओं को अपने डेटा को नियंत्रित करने की अनुमति दी जाए। यह कोई समस्या नहीं है,हैलो कहो होमोमोर्फिक एन्क्रिप्शन को। इस मुद्दे को सिर्फ टोपोलॉजी से निपटने के बजाय, हमें वेब के हर पहलू में कुछ नया करने और अपनी वेब सेवाओं से अधिक पूछने की आवश्यकता है। पुरानी प्रौद्योगिकी समस्या की तुलना में वेब की टोपोलॉजी समस्या मामूली है। अगर ये वेब 3.0 परियोजनाएं वास्तव में वेब को बदलने की परवाह करते हैं तो वे वास्तविक मुद्दों पर ध्यान केंद्रित करेंगे। **दोनों टोपोलॉजी के पास उनके अपने मामले हैं, लेकिन साथ मिल कर एक बढ़ती समस्या का समाधान हैं जो अनियंत्रित हो गयी है।**

## यूनिवर्सल वेब क्रिप्टोग्राफी ([सोडियम-नेटिव](https://github.com/sodium-friends/sodium-native))

-  प्रमुख हस्ताक्षर
    -   एकल-भाग हस्ताक्षर: Ed25519
    -   बहु-भाग हस्ताक्षर: Ed25519ph
-  पुलिंदा एन्क्रिप्शन
	- प्रमाणीकृत एन्क्रिप्शनअतिरिक्त डेटा के साथ
    - गोपनीय रखने के लिए किसी संदेश को कुंजी और नोन्स के साथ एन्क्रिप्ट करना
    - एक प्रमाणीकरण तागा की गणना करता है। इस तागा का उपयोग यह सुनिश्चित करने के लिए किया जाता है कि संदेश, साथ ही वैकल्पिक, अगोपनीय (गैर-एन्क्रिप्टेड) डेटा, के साथ छेड़छाड़ नहीं की गई है।
    - एन्क्रिप्शन: XChaCha20 stream cipher
    - प्रमाणीकरण: Poly1305 MAC

-  प्रमुख विनिमय - साझा सत्र कुंजी
    - BLAKE2B-512
        - BLAKE2 एक क्रिप्टोग्राफ़िक हैश फ़ंक्शन MD5, SHA-1, SHA-2 और SHA-3 से अधिक तेज़ है, फिर भी नवीनतम SHA-3 के तुलना में कम सुरक्षित है
        - 64-बिट प्लेटफ़ॉर्म के लिए विकसित किया गया है - NEON समेत- सक्षम ARMs - और 1 और 64 बाइट्स के बीच किसी भी आकार के डाइजेस्ट का उत्पादन करता है
    - X25519 – Ephemeral Key Pair
        - भेजनेवाले और पानेवाले के बीच साझा किए गए एक रहस्य की गणना करता है, भेजनेवाले की गुप्त कुंजी और पानेवाले की सार्वजनिक कुंजी (या इसके विपरीत) का उपयोग कर

## हाइब्रिड नेटवर्क
![हाइब्रिड नेटवर्क](https://github.com/sentivate/Sentivate-Network-White-Paper/blob/master/images/hindi_1.png)

## प्रोटोकॉल

### यूनिवर्सल डेटा स्ट्रीम प्रोटोकॉल
###### डेटा ट्रांसपोर्ट प्रोटोकॉल 

UDSP एक UDP आधारित कम-विलंबता, वास्तविक समय, द्वि-दिशात्मक, एन्क्रिप्टेड और विश्वसनीय डेटा ट्रांसपोर्ट प्रोटोकॉल है।

##### समस्या
जैसा कि परिचय में उल्लेख किया गया है: उपयोगकर्ता की मांगें बदल गई हैं और हमारी वेब की आवश्यकताएं बढ़ गई हैं। ये परिवर्तन HTTP को एक बड़ी मुश्किल बनाते हैं। HTTP और TCP दोनों ही बहुत बड़े मुद्दे हैं। बड़े डेटा केंद्र में एक छोर से दूसरे छोर तक डेटा की प्रचुर मात्रा चलती हैं, जिसमें विलंबता और लागत मुद्दे हैं जो पुरानी इंटरनेट वास्तुकला से जुडी है। HTTP विशेष रूप से समस्याग्रस्त है जब उपयोगकर्ता को कम थ्रूपुट, सीमित बैंडविड्थ, निम्‍नीकृत नेटवर्क कनेक्टिविटी का अनुभव होते हैं या वास्तविक समय की प्रतिक्रिया की आवश्यकता है।

##### समाधान
यूनिवर्सल वेब के निर्माण में पहला कदम HTTP को पूरी तरह से UDSP से बदलना है। UDSP एक UDP आधारित कम-विलंबता, वास्तविक समय, द्वि-दिशात्मक, एन्क्रिप्टेड और विश्वसनीय डेटा ट्रांसपोर्ट प्रोटोकॉल है। यूनिवर्सल वेब पर सभी संचार, स्ट्रीमिंग, या किसी भी प्रकार के डेटा का स्थानांतरण UDSP का उपयोग करते हैं। यूनिवर्सल वेब पर किसी साइट पर जाने पर UDSP वह प्रोटोकॉल है जिसका उपयोग HTTP के बजाय किया जाता है। विशिष्ट UDSP क्लाइंट और सर्वर मॉड्यूल को सेंटिवटे नेटवर्क पर किसी वेबसाइट पर जाने या होस्ट करने की आवश्यकता होती है। UDSP सेंटिवटे नेटवर्क का जीवन रक्त और आधार  है।

UDSP कनेक्शन स्तर पर गतिशील विश्वसनीयता के लिए सक्षम है या प्रति-अनुरोध के आधार पर जिसमें शामिल पक्षों के बीच सहमति हो। UDSP एन्क्रिप्शन लागू करता है जिसका अर्थ है कि सभी UDSP संपर्क पूर्वचयनित रूप से एन्क्रिप्ट किए गए हैं, कोई अपवाद नहीं है। UDSP IPv6, मल्टीप्लेक्सिंग और मल्टीहोमिंग का समर्थन करता है। UDSP एक कनेक्शन स्थापित करने के लिए क्रिप्टोग्राफ़िक कीपेयर्स और XChaCha20 पर निर्भर करता है।

UDSP वास्तविक समय के वेब और डिस्पेर्सेड कम्प्यूटिंग को प्राथमिकता देता है। चूँकि कनेक्शन द्वि-दिशात्मक हैं और कम बातूनी है यह नेटवर्क को कम भरा हुआ बनाता है और कनेक्शन की आजीविका के लिए कम विलंबता सुनिश्चित करता है। UDSP HTTP की तुलना में बहुत कम बातूनी है और इसे स्वयं की विश्वसनीयता मानकों को समायोजित करने के लिए प्रोग्रामेटिक रूप से सेट किया जा सकता है। यह UDSP को एक उच्च उपयोगी प्रोटोकॉल बनाता है जहाँ उच्च-थ्रूपुट, कम-विलंबता और उच्च विश्वसनीयता की आवश्यकता होती है। UDSP के प्रोग्रामेटिक रूप से गतिशील प्रकृति के कारण, यह अत्यधिक परिवर्तनशील और या अस्वीकृत नेटवर्क कनेक्टिविटी की स्थितियों में प्रभावोत्पादक है।

UDSP में वैकल्पिक पहेलियाँ शामिल हैं पैकेट में जो प्रदान कर्ता और समाधानकर्ताओं को VIAT कमाने की अनुमति देती हैं। पहेलियाँ अलग-अलग हो सकती हैं और इस्सलिये पहेलियाँ एक क्रियाशील-प्रमाण-कार्य हैं। पहेली को समझाया जा सकता है या डेटा को इंगित किया जा सकता है जो पहेली को हल करने के लिए आवश्यक है। यह कार्यक्षमता VIAT के अगले वाइट पेपर में वर्णित की जाएगी। पहेलियाँ भी भीड़ नियंत्रण के रूप में कार्य करती हैं और DDOS हमलों से संभावित नुकसान को सीमित करने का तरीका है। सेंटिवटे विभिन्न प्रकार पहेली को पैकेट में लाकर एक विशिष्ट डीडीओएस हमले को लाभ में बदल देता है। जब कोई ग्राहक दी गई पहेली को हल करता है तो क्लाइंट और डोमेन को नेटवर्क द्वारा आकलित किया जाता है Viat। यदि कोई सर्वर DDOS हमले के अंतर्गत है, तो सर्वर डोमेन के लिए इनाम विभाजन को 100% तक गतिशील रूप से बदल सकता है। यह सुनिश्चित करता है कि हमलावर अधिक वित्तीय नुकसान झेलें और उसको लाभ कम हो। पहेलियाँ यह सुनिश्चित करती हैं कि दोनों पक्षों के पास सद्भाव में कार्य करने के लिए एक प्रोत्साहन है।

![CLIENT CONNECTION](https://github.com/sentivate/Sentivate-Network-White-Paper/blob/master/images/hindi_2.png)

## यूनिवर्सल डोमेन सिस्टम

### डोमेन प्रमाण पत्र
###### राउटिंग तथा क्रिएटग्राफिक पैरामीटर

डोमेन प्रमाणपत्र राउटिंग प्रदान करते हैं, क्रिप्टोग्राफी तथा होस्टनाम से जुड़े अतिरिक्त विवरण प्रदान करते हैं। डोमेन प्रमाण पत्र पर 3 या अधिक प्रमुख कुंजी जोड़े द्वारा हस्ताक्षरित होते हैं: अल्पकालिक, मास्टर, और एक अधिकृत डोमेन पंजीयक। एक सफल हाथ मिलाव स्थापित करने के लिए, डोमेन प्रमाणपत्र और एक वैध हस्ताक्षर की आवश्यकता होती है।

डोमेन का अल्पकालिक प्रमाण पत्र एक बटुए के रूप में भी काम करता है जो ग्राहकों के लिए वितरित किसी भी पहेली के लिए धन संग्रहीत करता है। खनन किए गए Viat के एक हिस्से को अल्पकालिक प्रमाण पत्र बटुए के पते पर भेजा जाता है।

### डोमेन पंजीयक
###### अपलोड तथा साइन डोमेन पंजीयक

डोमेन पंजीयक का उपयोग डोमेन को पंजीकृत करने और डोमेन के सार्वजनिक प्रमाणपत्र का प्रबंधन करने के लिए किया जाता है। डोमेन पंजीयक होस्टनाम से जुड़े सार्वजनिक प्रमाणपत्रों को मान्य और हस्ताक्षरित करता है। फिर डोमेन पंजीयक प्रमाणपत्र को डोमेन सूचना प्रणाली में भेजता है जो वितरण के लिए प्रमाण पत्र संग्रहीत करता है।

### डोमेन सूचना प्रणाली
###### डोमेन राउटिंग की जांच तथा क्रिप्टोग्राफी

डोमेन सूचना प्रणाली, मानव-पढ़ने योग्य होस्टनाम से डोमेन प्रमाणपत्र के रूप में डोमेन-विशिष्ट जानकारी लौटाती है। DIS ने डोमेन का प्रमाणपत्र लौटाया जिसमें क्रिप्टोग्राफ़िक विवरण और राउटिंग जानकारी शामिल है। राउटिंग जानकारी के साथ होस्टनाम क्रिप्टोग्राफी को शामिल करके,0-RTT संभव है ग्राहक को पहले डोमेन पर जाने की आवश्यकता नहीं है । यह TLS 1.3 पर एक अनोखा लाभ है जिसमें 0-RTT पूर्वचयनित रूप से उपलब्ध है जहां टीएलएस 1.3 में किसी को पहले साइट पर जाना होगा। इससे पहले कि ग्राहक किसी वेबसाइट से जुड़े, उन्हें पहले DIS को मानव-पढ़ने योग्य होस्टनाम के साथ जाँच करना होगा । DIS में केंद्रीयकृत सर्वर और एक विकेंद्रीकृत नेटवर्क है डोमेन प्रमाणपत्र तक पहुँचने के लिए सबसे तेज़ संभव तरीके ग्राहकों को प्रदान करने के लिए।

DIS द्वेषपूर्ण प्रमाणपत्र संबंधित हमलों से बचाव की एक और परत के रूप में कार्य करता है। जब किसी सेवा में जाने के लिए DIS से जानकारी का अनुरोध करने के लिए अमान्य प्रमाणपत्र का उपयोग किया जाता है, तो DIS प्रतिक्रिया देने से इनकार करता है।

डोमेन प्रमाणपत्र प्रदान करने वाले विकेन्द्रीकृत नोड्स के पास उनके सेवाओं के माध्यम से Viat कमाने का मौका है। इस कार्यक्षमता को Viat व्हाइट पेपर के साथ गहराई से आवृत किया जाएगा।

![DIS](https://github.com/sentivate/Sentivate-Network-White-Paper/blob/master/images/hindi_3.png)

### डोमेन
###### मानव पठनीय होस्टनाम

सेंटिवटे पर डोमेन के पास पूर्ण एक्सटेंशन नाम हैं और ट्रेडमार्क वाले संस्थाओं के लिए अकेला पूरा नाम हो सकता है। डोमेन नियमों और विनियमों को वेब को व्यवस्थित करने, नई कंपनियों के लिए डोमेन नाम मुक्त, ट्रेडमार्क की रक्षा, दुर्भावनापूर्ण गतिविधि को सीमित करने और आयतन को अधिक वर्णनात्मक बनाने के लिए बनाया गया है।

उदाहरण के लिए, कोई केवल अमेज़ॅन को सेंटिवटे ब्राउज़र में अनुलेखन करके अमेज़ॅन पर जा सकता है। डोमेन नियम सेंटिवटे नेटवर्क पर कठोर हैं। डोमेन स्क्वेटिंग पूरी तरह से अस्वीकृत है, इसका नीति उपयोग करना या इसे खोना है। डोमेन सामग्री या सेवा डोमेन आयतन के अनुरूप होनी चाहिए। उदाहरण के लिए, अमेज़ॉन के स्टोर को स्टोर डोमेन आयतन, "Amazon.store" का उपयोग करना चाहिए। कुछ डोमेन के लिए आशुलिपि डोमेन एक्सटेंशन उपलब्ध हैं। उदाहरण के लिए, अमेज़ॅन की कंपनी की वेबसाइट को, Amazon.company या आशुलिपि मे Amazon.com का उपयोग करना होगा। बिटकॉइन, एथेरियम, और लाइटकॉइन  क्रिप्टोक्यूरेंसी हैं और उन्हें समर्पित साइटें क्रिप्टोक्यूरेंसी एक्सटेंशन का उपयोग करना चाहिए। हालांकि, बिटकॉइन से संबंधित एक समाचार साइट को .news और या .blog एक्सटेंशन का उपयोग करना होगा। कोई भी डोमेन जिसमें अनियमित या मनमानी सामग्री हो सकती है .abstract एक्सटेंशन का उपयोग करना चाहिए।

## सार्वत्रिक पहचान प्रणाली

### पहचान प्रमाण पत्र
###### अल्पकालिक तथा मुख्य कुंजी जोड़ा

पहचान प्रमाण पत्र, दस्तावेज हैं जो क्रिप्टोग्राफिक विवरण प्रदान करते हैं जो आपको नेटवर्क पर प्रतिनिधित्व करते हैं और एक पहचान पंजीयक द्वारा हस्ताक्षरित होते हैं। एक पहचान प्रमाण पत्र में दो क्रिप्टोग्राफिक कुंजी जोड़े होते हैं: अल्पकालिक तथा मुख्य। मुख्य कुंजी जोड़ा विशेष रूप से अल्पकालिक प्रमाण पत्र पर हस्ताक्षर करने के लिए उपयोग की जाती है और केंद्रीय पहचान कुंजी जोड़ा है। अल्पकालिक कुंजी जोड़े को मालिक के निर्णय पर  बदला जा सकता है। पहचान प्रमाणपत्र क्रिप्टोग्राफिक रूप से प्रमाणित और अधिकृत करता है ग्राहकों को नेटवर्क पर ।.

अल्पकालिक प्रमाण पत्र, मुख्य प्रमाण पत्र के लिए एक उप-प्रमाणपत्र हैं। अल्पकालिक प्रमाण पत्र प्रोफाइल के रूप में कार्य करता है जिसका उपयोग उपयोगकर्ता परिभाषित सेवाओं तक पहुंचने के लिए किया जाता है। उदाहरण के लिए, बटुआ प्रमाणपत्र, बैंकिंग प्रमाणपत्र, सामान्य वेब ब्राउज़िंग प्रमाणपत्र या सभी सेवा के लिए। हालांकि, सभी सेवाओं के लिए एकल अल्पकालिक प्रमाण पत्र का उपयोग करना चुन सकते हैं। अल्पकालिक प्रमाण पत्र का उपयोग प्रमुख विनिमय प्रक्रिया के लिए किया जाता है जो मूल और मेजबान के बीच द्वि-दिशात्मक UDSP संबंध स्थापित करता है।

उपयोगकर्ता तुरंत साइनअप, लॉगिन और अपने पहचान प्रमाणपत्र से किसी वस्तु को खरीद सकते हैं। सफल UDSP हाथ मिलाव को स्थापित करने के लिए सर्वर को संपर्क करने पर ग्राहक प्रमाणपत्र की आवश्यकता होती है।

पहचान प्रमाण पत्र विकेंद्रीकृत प्रतिष्ठा प्रणाली का आधार बनाते हैं, जो विशिष्ट प्रमाणपत्रों से जुड़े अच्छे और बुरे व्यवहार को सार्वजनिक रूप से अभिलेख कर सकते हैं। एक शहद बर्तन का उपयोग जाना माना खराब अभिनेता को रोकने के लिए सेवा से दूर किया जा सकता है नेटवर्क को सुरक्षित करने के लिए।

पहचान प्रमाणपत्र वास्तविक दुनिया की पहचान और संपत्ति से जुड़ा हो सकता है। सेंटिवटे को एक आदर्श मंच बनाना चुनावों में सुरक्षित, निजी और सत्यापन योग्य मतदान के लिए। दुकान और कंपनियों के पास सत्यापित पहचान प्रमाणपत्र हो सकता है जो उपयोगकर्ताओं को सीधे Viat के माध्यम से भुगतान करने या दान करने की अनुमति देता है।

### पहचान पंजीयक
###### वैधता और हस्ताक्षर

पहचान पंजीयक, एक सेवा है जो प्रमाणपत्रों पर हस्ताक्षर करती है और नेटवर्क के लिए सुरक्षा की पहली परत है। पहचान पंजीयक दोषपूर्ण प्रमाणपत्रों को छान कर, सिबिल हमलों से और नापाक अभिनेताओं से नेटवर्क की सुरक्षा करता है। पहचान पंजीयक यह सुनिश्चित करता है कि दुर्भावनापूर्ण प्रमाणपत्र हस्ताक्षरित नहीं हैं जो सेवाओं को उनके कनेक्शन प्रयासों को कुशलता से अस्वीकार करने की अनुमति देता है। DIS द्वारा गलत हस्ताक्षर को इनकार किया जा सकता है और इसलिए संभावित रूप से सेवा और संसाधनों को बचाया जा सकता है।

एक विकेन्द्रीकृत नेटवर्क और एसाइक्लिक ब्लॉकचेन पर हस्ताक्षर करने के लिए नए प्रस्तुत प्रमाण पत्रों को मान्य करने में मदद के लिए लाभ उठाया जाएगा। यदि प्रमाणित सफलतापूर्वक नेटवर्क द्वारा निरीक्षण किया गया है तो पहचान पंजीयक प्रमाणपत्र पर हस्ताक्षर करता है। फिर इसे सेवाओं और DIS द्वारा सफलतापूर्वक उपयोग किया जा सकता है। शुरुआती हाथ मिलाव के दौरान, पहले पुलिंदा में UDSP स्ट्रीम स्थापित करने के लिए आवश्यक प्रमाण पत्र होते हैं।

सक्रिय प्रमाणपत्र लगातार आधुनिक और हस्ताक्षरित रहेंगे। जब एक प्रमाण पत्र पर फिर से हस्ताक्षर किए जाते हैं, तो प्रमाण पत्र में एक और क्षेत्र जोड़ा जाता है जो प्रमाणपत्र के पिछले हस्ताक्षर के बाद बीता हुआ समय दिखाता है। यह प्रमाणपत्रों के लिए विश्वास की एक अतिरिक्त परत के साथ सेवाएं प्रदान करता है।

## विकास

### hApps
###### उच्चकोटी विश्वव्यापी वेब ऐप्स

उच्चकोटी एप्स स्व निर्माण, स्ट्रीमिंग सिंगल-पेज-एप्लिकेशन हैं। उच्चकोटी एप्लिकेशन को प्रतिक्रियाशील, गतिशील और मॉड्यूलर विकास विधियों का उपयोग करके बनाया गया है। hApps मे केंद्रीकृत और विकेन्द्रीकृत नेटवर्क के सभी लाभ हैं जो उच्चतम स्केलेबिलिटी क्षमता को सुनिश्चित करते हैं।

hApps की संपत्ति उनकी अपनी फ़ाइल में समाहित होती है और ग्राहक को आवश्यकता आधार पर प्रवाह की जाती है। hApps को समय पर बनाया जाता है और एक पुल के निर्माण की तरह ही समय के साथ बनाया जाता है। केवल एक प्रारंभिक पृष्ठ लोड होता है और उसके बाद पृष्ठ गतिशील रूप से एकल-पृष्ठ-ऐप के समान होते हैं। केवल तभी जब ग्राहक को संसाधन की आवश्यकता होती है लाया और वितरित किया जाता है।

सेंटिवटे के घटक अत्यधिक मॉड्यूलर संपत्ति प्रवाह के लिए अनुमति देते हैं। उदाहरण के लिए, घटक समान CSS या HTML परिसंपत्तियों को साझा कर सकते हैं जो यह सुनिश्चित करता है कि साझा परिसंपत्तियां केवल एक बार डाउनलोड की जाती हैं और नक़ल कोड को तार पर कभी नहीं भेजा जाता है। सर्वर लोड और बैंडविड्थ इस पद्धति से बहुत कम हो गया है क्योंकि अब ग्राहक केवल वही ले रहा है जिसकी आवश्यकता है। 

उच्चकोटी एप्स गंतव्य सेवा के अतिरिक्त संपत्तियों के लिए ऑप्ट-इन विकेंद्रीकृत P2P CDN का उपयोग कर सकते हैं । उच्चकोटी सामग्री वितरण नेटवर्क का उपयोग करने का मतलब है कि उच्चकोटी ऐप में उच्च उपलब्धता, मापनीयता और अधिक बैंडविड्थ। 

hAPPs प्रारंभिक हाथ मिलाव कनेक्शन के दौरान ग्राहकों को स्वचालित रूप से मान्य, प्रमाणित और अधिकृत करता है। hApps उनकी सार्वजनिक कुंजी या पूर्ण प्रमाणपत्र द्वारा ग्राहकों को भंडार और संदर्भ दे सकते इसे पूरे इंटरनेट के लिए OAuth समझिए। सेवाओं को अब हैशिंग, भंडारण और पासवर्ड को एन्क्रिप्ट करने के बारे में चिंता करने की आवश्यकता नहीं है। ग्राहक बस एक बटन पर दबा कर या केवल सेवा से जुड़कर स्वचालित रूप से लॉगिन कर सकते हैं। उपयोगकर्ताओं को अब जटिल पासवर्ड याद रखने या बनाने की आवश्यकता नहीं है क्योंकि उनके कुंजी जोड़े का उपयोग करना अधिक सुरक्षित और उपयोग में आसान है। यदि सेवाओं के लिए आपको एक उपयोगकर्ता नाम की आवश्यकता नहीं है, तो वे आपके पहचान के रूप में आपकी सार्वजनिक कुंजी पर भरोसा कर सकते हैं। इसका मतलब यह है कि कुछ सेवाओं के लिए उपयोगकर्ताओं को पंजीकरण प्रक्रिया के दौरान उपयोगकर्ता नाम और पासवर्ड बनाने की आवश्यकता नहीं है।

## VIAT

### देशी क्रिप्टोकरेंसी
Viat सेंटिवटे नेटवर्क पर देशी क्रिप्टोकरेंसी है। Viat में एक उच्चकोटी  ब्लॉकचेन है। Viat की मुख्य प्रणाली विकेंद्रीकृत हैं लेकिन केंद्रीकृत घटकों द्वारा बढ़ाया जाता है।(सेंटिवटे के वेब के विपरीत) । Viat को तेज़, सुरक्षित और कुछ सबसे कम लेनदेन शुल्क उपलब्ध कराने के लिए बनाया गया है। Viat के केंद्रीकृत हिस्से तत्काल लेनदेन की प्रक्रिया कर सकते हैं, बटुआ सुरक्षा प्रदान कर सकते हैं, और विकेंद्रीकृत नेटवर्क भारी  नेटवर्क भीड़ को कम कर सकते हैं। हालाँकि, ये केंद्रीकृत सुविधाएँ केवल ऑप्ट-इन उपयोगकर्ताओं को अपना रास्ता बनाने की अनुमति देती हैं।

### खनन 
Viat के पास काम का एक गतिशील प्रमाण है जिसे दो तरीकों से खनन किया जा सकता है। प्रत्यक्ष खनन मुख्य विधि है, जिसे Viat व्हाइट पेपर में समझाया जाएगा, और दूसरी विधि UDSP में पुलिंदा पहेली के उपयोग के माध्यम से। विश्वव्यापी वेब चलाने समय पुलिंदा पहेली Viat के निष्क्रिय खनन की अनुमति देते हैं। हालाँकि, यह पूर्वचयनित रूप से सक्षम नहीं है। जो परिस्थितियाँ उत्पन्न होती हैं जो पुलिंदा पहेली को सक्षम करती हैं: संपर्क हाथ मिलाव, संपर्क आजीविका की जाँच,DDoS पसुरक्षा, भीड़ नियंत्रण और सेवा इसे अपने स्वयं के कारणों से सक्षम करना चुनता है। पुलिंदा पहेली को सक्षम करने के लिए सेवा पर निर्भर है। यह सुनिश्चित करता है कि पृष्ठभूमि में निरंतर खनन की कोई आवश्यकता नहीं है और खनन प्रक्रिया को वास्तविक उद्देश्य देता है। अन्यथा, यह हर समय संसाधनों को चूसने और बैटरी जीवन को ख़तम करता रहेगा।

### INTEROPERABILITY 
पहचान और डोमेन प्रमाण पत्र भी Viat बटुआ कुंजी के रूप में दोगुना होता है। यह उपयोगकर्ताओं को न केवल एक संपर्क हाथ मिलाव के दौरान एक सेवा में तुरंत हस्ताक्षर करने की अनुमति देता है, बल्कि सेवाओं, युक्तियाँ साइटों और ग्राहकों को धन की वापसी का एक तरीका भी प्रदान करता है। Viat विश्वव्यापी वेब की पूर्ण कार्यक्षमता का एक अभिन्न हिस्सा है, इसके बिना केवल चित्र का हिस्सा है।
