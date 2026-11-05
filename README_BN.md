# HSC Preparation Tracker — Updated Starter

এই সংস্করণে প্রত্যেক শিক্ষার্থী নিজের অ্যাকাউন্টে নিজের বিষয় যোগ করতে পারবে এবং নিজের অধ্যায় যোগ, সংশোধন ও মুছতে পারবে। শুরুতে বাংলা ১ম/২য়, ইংরেজি ১ম/২য় ও ICT ডিফল্ট বিষয় হিসেবে আসবে।

## Firebase সেটআপ
1. https://console.firebase.google.com/ এ প্রজেক্ট তৈরি করুন।
2. Web App যোগ করে Firebase config `app.js`-এ বসান।
3. Authentication → Sign-in method → Email/Password চালু করুন।
4. Firestore Database তৈরি করুন।
5. Firestore Rules-এ `firestore.rules`-এর নিয়ম বসিয়ে Publish করুন।
6. VS Code Live Server দিয়ে চালান অথবা Firebase Hosting-এ deploy করুন।

প্রকাশের আগে email verification, password reset, privacy policy, App Check এবং দুইটি আলাদা শিক্ষার্থী অ্যাকাউন্ট দিয়ে security rules পরীক্ষা করুন।


## ডিফল্ট ১৬টি বিষয়
- বাংলা ১ম
- বাংলা ২য়
- ইংরেজি ১ম
- ইংরেজি ২য়
- আইসিটি
- ইসলামের ইতিহাস
- বালাগাত
- মানতিক
- আরবি ১ম
- আরবি ২য়
- ফিকহ ১ম
- ফিকহ ২য়
- কুরআন
- হাদিস
- পৌরনীতি ১ম
- পৌরনীতি ২য়
