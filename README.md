# Build-Week--Social-Media-Content-Scheduler
# The Creation Buzz – Social Media Content Scheduler 🗓️📱

**The Creation Buzz** is a fully responsive web application that helps users schedule and manage posts across multiple social media platforms including Instagram, Facebook, LinkedIn, X (Twitter), and YouTube.

## 🔍 Overview

This app offers:
- User authentication with Firebase
- Adding and storing user account details
- Scheduling posts by date and time
- Posting simultaneously to multiple platforms
- Viewing and managing plans and testimonials
- Contact and feedback form with Google Maps integration

## 🚀 Features

- ✅ User Signup/Login (via Firebase Auth)
- ✅ Add and manage multiple social media accounts
- ✅ Upload images with caption and trending hashtag suggestions
- ✅ Schedule future posts with time delay logic
- ✅ Responsive design using CSS and Bootstrap
- ✅ Contact form that sends queries via email
- ✅ Five tiered subscription plans
- ✅ Beautiful testimonials and footer UI

## 🛠 Tech Stack

| Area        | Tech Used                               |
|-------------|------------------------------------------|
| Frontend    | HTML5, CSS3, JavaScript                  |
| Styling     | Bootstrap 5, Google Fonts, Font Awesome  |
| Backend     | Firebase Realtime Database, Firebase Auth|
| Deployment  | Ready for GitHub Pages / Netlify hosting |
| Utilities   | FormSubmit for contact form              |

## 📁 Project Structure

```
/
├── index.html                  # Home page
├── index.css                   # General styles
├── /frontend/
│   ├── pages/
│   │   ├── profile.html
│   │   ├── plans.html
│   │   ├── calender.html
│   ├── forms/
│   │   ├── signin.html
│   │   ├── signup.html
│   │   ├── addAccount.html
│   │   ├── form.css
│   │   ├── account.css
│   ├── images/
│       ├── favicon, logos, etc.
```

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/the-creation-buzz.git
   ```

2. Open `index.html` in a browser.

3. For Firebase features:
   - Create a Firebase project
   - Add your project config inside `signin.html` and `signup.html`
   - Set rules for authentication and database access

## 🔒 Authentication

- Login system stores session in `localStorage`
- User profile photo and name are shown only if logged in
- On login: data is saved to Firebase Realtime DB

## 📦 Plans Page

Includes five types of packs:
- Bronze
- Silver
- Gold
- Platinum
- Special (AI Pack)

Each includes unique descriptions and styled cards with hover effects.

## 📆 Calendar (Post Scheduler)

Users can:
- Select a title, date, and time
- Schedule a post with `setTimeout()`
- See live status as “Scheduled” or “Posted”

## 💬 Testimonials

Includes user feedback with styled cards:
- Cristiano
- Mr. Beast
- Faisu

## 📮 Contact Us

- Form: Name, email, and message
- Integrated with FormSubmit
- Google Maps iframe for location

## 🧑‍💻 Author

- **Name:** MR. SHAIKH Altamash  
- **Email:** mr.shaikh.altamash0203@gmail.com

## 📄 License

Open source under the [MIT License](LICENSE)

## 📷 Screenshots (optional)

> Add UI screenshots here for better visual appeal

## 📷 Screenshots

### 🔹 Home Page
![Home Page](/screenshots/home.png)

### 🔹 Post Scheduler
![Post Scheduler](/screenshots/calender.png)

### 🔹 Profile page
![user profile](/screenshots/profile.png)