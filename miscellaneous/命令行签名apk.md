```
签名：
使用jarsigner.exe(位于%JAVA_HOME%\bin\jarsigner.exe)签名
C:\Java\jdk1.8.0_31\bin\jarsigner -verbose -keystore android.keystore -signedjar drastic_Signed.apk drastic.apk android.keystore

说明：
-verbose 输出签名的详细信息
-keystore android.keystore 密钥库位置
-signedjar drastic_Signed.apk drastic.apk android.keystore 正式签名，drastic_Signed.apk drastic.apk分别为签名后生成的apk和原始apk
三个参数中依次为签名后产生的文件drastic_Signed.apk，要签名的文件drastic.apk和密钥库android.keystore

F:\code\psp_cocos\proj.nds.crack\bin>C:\Java\jdk1.8.0_31\bin\jarsigner  -digestalg SHA1 -sigalg MD5withRSA -keystore android.keystore -signedjar drastic_Signed.apk drastic.apk android.keystore  -tsa http://timestamp.digicert.com

输入密钥库的密码短语:123456
```
