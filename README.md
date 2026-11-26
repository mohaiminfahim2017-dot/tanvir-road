# তানভীর ও অচেনা রাস্তা — Remotion প্রজেক্ট (১৬:৯, ১৯২০×১০৮০, ৩০fps)

```
npm install
npx remotion studio src/index.ts     # প্রিভিউ
npx remotion render src/index.ts TanvirRoad out/video.mp4   # রেন্ডার
```

- `public/voice.mp3` — ভয়েসওভার, `public/bgm.mp3` — হরর ব্যাকগ্রাউন্ড মিউজিক (ভলিউম ১৫%)
- `src/data/timeline.ts` — সিনের সময় ও বাবল/ক্যাপশন উইন্ডো; `src/data/captions.ts` — SRT থেকে ক্যাপশন
- `src/components/Character.tsx` — তিন ক্যারেক্টার (এক্সপ্রেশন + লিপ-সিঙ্ক); `src/scenes/` — সিন ১–৭
