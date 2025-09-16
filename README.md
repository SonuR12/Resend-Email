# ✉️ Resend Email - Contact Form Integration

A simple and modern **Contact Form** built with Next.js, React, and TailwindCSS that integrates with **Resend API** to send emails seamlessly.  
This project demonstrates how to collect user details (name, email, contact number, message) and forward them via email using **Resend**.

1[image](https://github.com/SonuR12/Resend-Email/blob/main/public/images/Demo.png)
---

## 🚀 Features
- 📩 Send emails directly from the contact form  
- 🎨 Modern UI with TailwindCSS  
- 🔒 Secure email handling with Resend  
- ✅ Form validation for better user experience  
- 🌍 Ready to deploy on **Vercel**  

---

## 📂 Project Structure

```bash
Resend-Email/
│── public/ # Static assets
│── src/
│ ├── app/
│ │ ├── api/
│ │ │ └── send/ # API route for sending emails with Resend
│ │ ├── components/
│ │ │ └── ContactForm.tsx # Contact form component
│ │ ├── page.tsx # Main page
│ │ └── layout.tsx # Root layout
│ ├── styles/ # Global styles
│── .env.local # Environment variables (Resend API key)
│── package.json # Dependencies and scripts
│── tailwind.config.js # TailwindCSS configuration
│── README.md # Documentation

```

---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/SonuR12/Resend-Email.git
   cd Resend-Email
   ```

2. Install dependencies:

   ```bash
    npm install
    # or
    yarn install
    ```

3. Add your Resend API Key in .env.local:
   ```bash
    RESEND_API_KEY=your_resend_api_key_here
   ```

4. Run the development server:
   ```bash
    npm run dev
   ```
5. Open http://localhost:3000 in your browser 🚀

   ---

## 📧 Email Sending (Resend API)

- The form submits data to `/api/send`  
- The API route uses the **Resend SDK** to send emails to your inbox  
- Example email format:
From: John Doe john.doe@example.com
Contact: +91 XXXXXXXX
Message: "Tell us about your travel plans or questions..."

---

## 📌 Tech Stack
- [Next.js](https://nextjs.org/)  
- [React](https://react.dev/)  
- [TailwindCSS](https://tailwindcss.com/)  
- [Resend](https://resend.com/)  

---

## 📜 License
This project is licensed under the **MIT License**.

