Bubble Blast Pro - Mobile se online APK build

Is project mein GitHub Actions workflow diya gaya hai. APK aapke phone par compile nahi hoga; GitHub ke cloud runner par build hoga.

1) GitHub.com par account banayein / login karein.
2) New repository banayein. Naam: BubbleBlastPro (Public ya Private).
3) Is ZIP ko phone mein extract karein.
4) Extract kiye project ke ANDAR ke sabhi files/folders (app, build.gradle, settings.gradle, .github samet) GitHub repository ke main page par Add file > Upload files se upload karein. ZIP ko seedha upload na karein.
5) Commit changes karein aur branch ka naam main rakhein.
6) Repository mein Actions tab kholein.
7) “Build Bubble Blast Pro APK” workflow select karein, Run workflow dabayein.
8) Build complete hone par workflow run ke neeche Artifacts mein BubbleBlastPro-debug-apk.zip download karein.
9) Artifact ZIP extract karein. app-debug.apk par tap karke install karein. Android pooche to Chrome/Files ko “Install unknown apps” permission deni pad sakti hai.

Agar upload ke waqt mobile browser mein dikkat ho, Chrome menu > Desktop site on karke koshish karein.

Note: Yeh debug APK testing ke liye hai, Play Store release ke liye signed release build alag se banana hoga. GitHub account aur internet chahiye. Actual rewarded ads abhi integrated nahi hain.
