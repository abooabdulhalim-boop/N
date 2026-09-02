موبائل سے AAB بنانے کا طریقہ:

1) GitHub پر نیا repository بنائیں۔
2) اس ZIP کو Extract کرکے تمام files repository میں upload کریں۔
3) Actions کھولیں۔
4) "Build Android AAB" workflow منتخب کریں۔
5) "Run workflow" دبائیں۔
6) Build مکمل ہونے پر workflow کے Artifacts میں "Noori-Book-Central-AAB" ZIP ڈاؤن لوڈ کریں۔
7) Artifact ZIP کے اندر .aab فائل ہوگی۔

نوٹ: یہ workflow release AAB بناتا ہے، لیکن Play Store کے لیے محفوظ/قابلِ قبول production release کے لیے signing key کا انتظام الگ ضروری ہے۔
