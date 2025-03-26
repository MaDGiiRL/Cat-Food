# 😽 Foodie - Powered by Laravel © Developed with ♡ by Sofia Vidotto

Welcome to **Foodie**, the ultimate platform for cat lovers! ὣAὣBὣD
A website entirely dedicated to selling **100% natural cat food** ὀ8, with an AI assistant ready to help you choose the best nutrition for your feline. 

---

## 🎨 Project Overview

**Foodie** is built with **Laravel 12** and uses **Laravel Fortify** to ensure secure authentication. Additionally, it integrates **Laravel Socialite** for social login, **OpenAI** for an intelligent AI assistant, and the API **https://api.thecatapi.com/** to fetch images and information about cats. ὣCὃ1

📌 **Main Features**:  
- 😽 **Natural Cat Food** – Explore a selection of healthy and nutritious food for cats ὣA.  
- 🤖 **AI Assistant** – Chat with the AI assistant for feline nutrition advice ὃ1.  
- 🔒 **Secure Access** – Only registered and verified users can make purchases ὣB.  
- 👥 **Social Login** – Easily register via Google, Facebook, or other social platforms ὣC.  
- 🌟 **Images & Info** – Get photos and details about various cat breeds via API 😽.  
- 🌚 **Dark Mode Interface** – A modern and elegant design, perfect for cat lovers ὣD.  

---

## 🛠️ Technologies Used

✔️ **Laravel 12** – Robust framework for backend development.  
✔️ **Laravel Fortify** – For user authentication management.  
✔️ **Laravel Socialite** – For social network login.  
✔️ **Livewire** – For real-time dynamic updates.  
✔️ **MySQL** – Database for managing products and users.  
✔️ **PHP** – Server-side scripting language.  
✔️ **HTML5 & CSS3** – For website markup and styling.  
✔️ **Bootstrap 5** – For a responsive and modern interface.  
✔️ **OpenAI** – Powers the AI chatbot.  
✔️ **The Cat API** – Fetches images and information about cats ὀ8.  

---

## 👅 Installation & Setup

Follow these steps to set up and run the project locally:

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/MaDGiiRL/foodie
cd foodie
```

### 2️⃣ Install Dependencies  
```bash
composer install
npm install
```

### 3️⃣ Generate the Key 
```bash
php artisan key:generate
```

### 4️⃣ Configure the Environment  
Rename `.env.example` to `.env` and set up your database credentials:  
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

Set your **OpenAI API Key** and **The Cat API Key** in `.env`:  
```env
OPENAI_API_KEY=your_openai_api_key
OPENAI_ORGANIZATION=your_openai_organization_id
CAT_API_KEY=your_cat_api_key
```

### 5️⃣ Run Migrations & Seed Database  
```bash
php artisan migrate --seed
```

### 6️⃣ Start the Development Server  
```bash
php artisan serve
```

Now open **http://127.0.0.1:8000/** in your browser to explore the website ὣA.

---

## 💡 Contributions & Improvements

Have suggestions? Want to contribute? Feel free to **submit a pull request** or open an **issue**! 🚀ὃ1