- 👋 Hi, I’m @Ailean2021
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ailean2021/Ailean2021 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
java.lang.RuntimeException: An error occurred while executing doInBackground()
	at android.os.AsyncTask$3.done(AsyncTask.java:354)
	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:383)
	at java.util.concurrent.FutureTask.setException(FutureTask.java:252)
	at java.util.concurrent.FutureTask.run(FutureTask.java:271)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
	at java.lang.Thread.run(Thread.java:764)
Caused by: java.lang.IllegalArgumentException: Unknown URI content://com.lbe.security.miui.permmgr
	at android.content.ContentResolver.call(ContentResolver.java:1769)
	at com.miui.permission.PermissionManager.getAllPermissions(Unknown Source:14)
	at com.miui.permcenter.permissions.l$a.a(Unknown Source:19)
	at com.miui.permcenter.permissions.l$a.loadInBackground(Unknown Source:0)
	at android.content.AsyncTaskLoader.onLoadInBackground(AsyncTaskLoader.java:319)
	at com.miui.common.i.a.onLoadInBackground(Unknown Source:0)
	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:73)
	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:61)
	at android.os.AsyncTask$2.call(AsyncTask.java:333)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	... 3 more
