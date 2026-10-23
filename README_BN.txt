
ফোন থেকেই APK বানানোর সহজ উপায় (GitHub Actions)
১) GitHub-এ একটি নতুন repository তৈরি করুন।
২) ZIP Extract করে এর ভেতরের সব ফাইল repository-তে Upload files দিয়ে আপলোড ও Commit করুন।
৩) repository-র Actions ট্যাবে যান; “Build Android APK” workflow খুলে “Run workflow” চাপুন (push করলেও নিজে থেকে build হবে)।
৪) build শেষ হলে workflow run-এর পেজের Artifacts থেকে ChakrabiddhiMunafa-debug-apk.zip ডাউনলোড করুন।
৫) ZIP Extract করে app-debug.apk ফোনে ইনস্টল করুন। Android চাইলে Settings-এ “Install unknown apps” অনুমতি দিতে হতে পারে।
নোট: এটি Debug APK; Play Store-এ প্রকাশের জন্য signed release APK আলাদা করে তৈরি করতে হবে।
