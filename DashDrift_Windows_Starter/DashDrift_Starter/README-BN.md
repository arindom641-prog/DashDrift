# Dash Drift — Android Starter

এটি একটি নতুন, হালকা Android WebView starter project। Package: `com.dashdrift.game`।

## এখন কী আছে
- ৩-লেনের সাধারণ 2D endless-runner prototype
- Android launcher activity ও WebView
- GitHub Actions workflow দিয়ে cloud-এ debug APK build
- Windows 10 / 4 GB RAM ল্যাপটপে Android Studio ছাড়াই cloud build করার পরিকল্পনা

## APK বানানোর জন্য পরের ধাপ
1. GitHub-এ একটি account তৈরি করুন।
2. এই ZIP extract করে `DashDrift` folder-এর সব ফাইল একটি নতুন GitHub repository-তে upload করুন।
3. Repository-তে **Actions** tab খুলুন।
4. `Build Dash Drift APK` workflow নির্বাচন করে **Run workflow** চাপুন।
5. Build শেষ হলে Artifacts থেকে `DashDrift-debug-apk` ZIP download করে extract করুন। ভিতরে `app-debug.apk` থাকবে।

## গুরুত্বপূর্ণ
- এটি এখনো prototype; Play Store release-ready নয়।
- Coin shop UI, six real Google Play Billing products, purchase-token verification backend, এবং server-side validation এখনো যোগ করা হয়নি।
- আগের নির্ধারিত মূল্য: $1.01, $2.01, $3.01, $4.01, $5.01, $5.51। Billing product ID ও Google Play Console setup করার আগে এগুলো live purchase হিসেবে কাজ করবে না।
- Debug APK ব্যক্তিগত পরীক্ষার জন্য; Play Store-এর জন্য signed release build ও Play Console setup প্রয়োজন।
