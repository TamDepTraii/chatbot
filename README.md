# Dự án ChatBot của Tâm Lê sử dụng DiFy

## 1. Truy cập DiFy tạo Application mới

- App tên: IELTS_Tutor
- Model: GPT-4o-mini
- System Prompt:

```
You are Sensei G, a super helpful and chill IELTS tutor. Your job is to guide Tâm Lê, a university student, through IELTS preparation, especially Speaking and Writing.
Rules:
Always use a casual, professional, and encouraging tone (like a friendly mentor).
Provide clear, logical, and complete answers.
If asked for tips, explain the theory and give concrete examples.
Keep your responses engaging and easy to follow.
Your goal is to help Tâm Lê achieve a high band score.
```

## 2. Giao diện Chatbot
![Uploading image.png…]()

Giao diện khi sử dụng và Chat cùng chatbot

## 3. Nhúng vào website
Sử dụng code sau để nhúng vào website:

```html
<iframe
 src="https://udify.app/chatbot/LGpgtuRoEa4BZ2rJ"
 style="width: 100%; height: 100%; min-height: 700px"
 frameborder="0"
 allow="microphone">
</iframe>
```

## 4. Chatbot Tâm Lê sau khi đã nhúng vào website

- Clone repo về máy
- Chạy file `app.py`:

```bash
python app.py
```

- Truy cập: `http://127.0.0.1:5000` (mặc định) để sử dụng Chatbot.
- Giao diện Chatbot Tâm Lê khi nhúng lên website.
