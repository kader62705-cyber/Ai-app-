# AI ረዳት — የአንድሮይድ ፕሮጀክት

## APK ለመስራት
1. Android Studio (ነጻ) ይጫኑ፤ ይህን ዚፕ ይፍቱ።
2. File > Open ብለው `AIApp` ፎልደሩን ይምረጡ፤ Gradle እስኪጨርስ ይጠብቁ።
3. Build > Build Bundle(s) / APK(s) > Build APK(s)።
4. ፋይሉ እዚህ ይገኛል፦ `app/build/outputs/apk/debug/app-debug.apk` — ስልክዎ ላይ ይጫኑት።

## የAPI ቁልፍ
አፑን ከፍተው ⚙️ ሴቲንግ > Anthropic API ቁልፍ ላይ ከ console.anthropic.com ያገኙትን ቁልፍ ያስገቡ።
ቁልፉ በስልክዎ ላይ ብቻ ይቀመጣል። ለሌሎች ሰዎች አፑን ከሚያካፍሉ ቁልፍዎን በውስጡ አያስቀምጡ።

## ስም መቀየር
`com.example.aiapp` ን በ`app/build.gradle` (namespace እና applicationId) እና በ`MainActivity.kt` ይቀይሩ።
የገጹ ኮድ `app/src/main/assets/index.html` ነው።

## Google ሎግኢን (አልተካተተም)
እውነተኛ Google/Gmail ሎግኢን የራስዎን Firebase ፕሮጀክት ይፈልጋል፦
1. console.firebase.google.com ላይ ፕሮጀክት ይክፈቱ፤ Authentication > Google ያብሩ።
2. አንድሮይድ አፕ ጨምረው `google-services.json` ወደ `app/` ያስገቡ (SHA-1 ያስፈልጋል)።
3. ከዚያ የGoogle ቁልፉን ለማገናኘት ንገሩኝ፣ ኮዱን እጽፍልዎታለሁ።
አሁን ያለው ሎግኢን በስልኩ ላይ ብቻ የሚቀመጥ አካባቢያዊ አካውንት ነው።
