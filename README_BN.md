# Bangla Voice Writer Pro — Android Starter

## এই সংস্করণে আছে
- Android app source project (Kotlin + Jetpack Compose)
- Android Speech Recognition service দিয়ে bn-BD ভয়েস ইনপুট
- বাংলা টেক্সট এডিটর
- Copy এবং UTF-8 TXT Save
- Voice / Avro / Bijoy এবং Unicode / SutonnyMJ UI selector

## এখনো নেই
- নিজস্ব offline speech model
- Avro phonetic keyboard engine
- Bijoy Classic-compatible keyboard engine
- Verified Unicode-to-Bijoy ANSI converter
- DOCX/PDF export
- APK binary

SutonnyMJ ফন্ট নির্বাচনটি এখন placeholder। Encoding converter ছাড়া Unicode text-কে
Bijoy ANSI বলা যাবে না। নির্ভুল character mapping ও test suite তৈরি করে পরের
ধাপে এই ফিচার যোগ করতে হবে।

## Build করার নিয়ম
1. Android Studio (recent stable) ইনস্টল করুন।
2. ZIP extract করুন।
3. Android Studio থেকে extracted `Bangla_Voice_Writer_Android` folder Open করুন।
4. Gradle sync সম্পন্ন হতে দিন।
5. Android ফোন USB debugging দিয়ে যুক্ত করুন অথবা emulator চালু করুন।
6. Run চাপুন।
7. APK বানাতে: Build > Build Bundle(s) / APK(s) > Build APK(s).

## ভয়েস ও গোপনীয়তা
অ্যাপটি Android-এর speech recognition service খুলে দেয়। এটি অনলাইন না অফলাইন হবে
তা ফোনের speech provider ও ডাউনলোড করা language pack-এর ওপর নির্ভর করে। গোপন
অফিসের তথ্য বলার আগে provider-এর privacy ও offline availability যাচাই করুন।
