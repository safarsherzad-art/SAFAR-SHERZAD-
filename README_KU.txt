SAFAR SHERZAD AI WORLD — وەشانی PWA بۆ زیادکردن لە شاشەی iPhone

ئەمە ڕووکارێکی وێبە کە دەتوانرێت لە Safari بکەیتە ئایکۆن لە شاشەی سەرەکی.
بەڵام بۆ وەڵامی AI و گەڕانی وێب، دەبێت backend بڵاو بکرێتەوە و API_BASE ڕێکبخرێت.

هەنگاوەکان:
1) ZIP بکەرەوە لە Windows 11.
2) فایلەکان index.html, manifest.json, sw.js, icon.svg لە خزمەتگوزارییەکی static hosting (وەک GitHub Pages) بڵاو بکەرەوە.
3) لە iPhone، بە Safari URL ـی وێبسایتەکە بکەرەوە.
4) Share → Add to Home Screen → Add.
5) بۆ AI، backend/server.js لە پڕۆژەی backend ـی پێشوو بە hosting ـێکی Node.js بڵاو بکەرەوە؛ API key تەنها لە server environment دابنێ.
6) URL ـی backend لە سەرەتای script لە index.html لە API_BASE دابنێ، پاشان دووبارە deploy بکە.

تێبینی: GitHub Pages تەنها فایلە static ـەکان میوانداری دەکات؛ backend ـی Node.js لەوێ کار ناکات.
بۆ ئەپی ئایفۆن، URL ـی HTTPS پێویستە. ئەم ZIP ـە APK/IPA نییە و بە تەنها وەڵامی AI نادات.
