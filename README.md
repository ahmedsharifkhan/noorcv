# Noor CV (Hugo-ready)

এই CV টেমপ্লেটটা Hugo project-এ সরাসরি ব্যবহার করার জন্য তৈরি করা হয়েছে।

## কী আছে
- Hugo `layouts/index.html` template.
- সব data `data/cv.yaml` এ রাখা আছে, যাতে আপনি সহজে content update করতে পারেন.
- সুন্দর responsive CV design (`static/css/cv.css`).
- Frontend থেকে resume download button.

## কিভাবে update করবেন
1. `data/cv.yaml` ফাইলে আপনার নাম, experience, skills, ইত্যাদি বদলে দিন.
2. আপনার আসল PDF resume `static/resume/ahmed-sharif-khan-resume.pdf` এর জায়গায় replace করুন.
3. প্রয়োজন হলে button link `data/cv.yaml`-এর `resume_file` field এ update করুন.

## Hugo run
```bash
hugo server -D
```
তারপর `http://localhost:1313` এ CV দেখুন.
