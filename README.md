# Abbas Abod Net

بعد الاستيراد، إن لم يكن مجلد android يحتوي ملفات gradle، نفّذ مرة واحدة داخل المشروع:

    flutter create --org com.abbas --project-name netanalyzer --platforms android .

(لن يمسح ملفاتك: main.dart و MainActivity.kt و AndroidManifest.xml و الأيقونات تبقى كما هي. إن طلب استبدالها فارفض.)

ثم: flutter pub get ثم flutter run

ملاحظة: اجعل minSdkVersion = 24 في android/app/build.gradle (أو build.gradle.kts).
