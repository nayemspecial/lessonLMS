<div align="center">

# 🎓 lessonLMS — WordPress LMS Theme

**A lightweight, plugin-free WordPress theme to build your own online course platform.**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![WordPress](https://img.shields.io/badge/WordPress-Theme-blue?logo=wordpress)](https://wordpress.org)
[![PHP](https://img.shields.io/badge/PHP-7.4%2B-777BB4?logo=php&logoColor=white)](https://php.net)
[![Stars](https://img.shields.io/github/stars/nayemspecial/lessonLMS?style=social)](https://github.com/nayemspecial/lessonLMS/stargazers)

[**🔴 Live Demo**](https://projuktiplus.com/lesson) · [**🐞 Report Bug**](https://github.com/nayemspecial/lessonLMS/issues) · [**✨ Request Feature**](https://github.com/nayemspecial/lessonLMS/issues)

![lessonLMS Screenshot](screenshot.png)

</div>

## Why lessonLMS?

Most WordPress LMS solutions depend on heavy plugins that slow down your site.
**lessonLMS** is a custom-coded WordPress LMS theme built only with core WordPress
APIs (Custom Post Types, Meta Boxes, Customizer, AJAX), so it stays fast, simple
and easy to customize. It is also a great real-world example for learning
WordPress theme development.

## ✨ Features

- 📚 **Course Custom Post Type** — create and manage courses from the dashboard
- 🧾 **Course Meta Boxes** — price, original price, video hours, article count, language, subtitles, "What you'll learn", requirements, target audience
- ⚡ **AJAX Enrollment** — enroll in a course with one click, no page reload
- ⭐ **Review & Rating System** — student reviews with automatic average rating and review count
- 🎨 **Full Customizer Support** — edit Hero, Features, CTA, Blog and Footer sections live
- 💬 **Testimonials** — dedicated custom post type for student testimonials
- 📊 **Admin Dashboard Widget** — total enrollments and latest student sign-ups at a glance
- 📱 **Responsive Design** — works on mobile, tablet and desktop
- 🧩 **Modular Code** — clean `inc/` and `template-parts/` structure
- 🧭 **Menus & Widgets** — Primary, Mobile, Footer menus and a Blog Sidebar

## 🛠️ Built With

PHP · WordPress APIs (CPT, Meta Box, Customizer, AJAX, Widgets) · JavaScript (jQuery) · CSS3 · Slick Slider · Boxicons · Font Awesome · MySQL

## ⚙️ Installation

1. **Download or clone**
```bash
   git clone https://github.com/nayemspecial/lessonLMS.git
```
2. Copy the folder to `wp-content/themes/`
3. Go to **Appearance → Themes** and activate **LessonLMS**
4. Go to **Settings → Permalinks** and click **Save Changes** (required, otherwise course pages show 404)
5. Set up menus, customize sections, and add courses from **Courses → Add New Course**

## 📂 Folder Structure

```
lessonLMS/
├── assets/            # CSS, JS, images
├── inc/
│   ├── admin/         # roles, dashboard redirect, capabilities
│   ├── cpt/           # courses & testimonials
│   ├── customizer/    # hero, feature, cta, blog, footer
│   ├── reviews/       # review submit & stats
│   └── student-enroll/# AJAX enrollment & admin data
├── template-parts/    # sections (hero, courses, cta, ...) & content
├── archive-course.php
├── single-course.php
├── front-page.php
├── functions.php
└── style.css
```

## 🗺️ Roadmap

- [ ] Prevent duplicate enrollments
- [ ] Nonce security for AJAX requests
- [ ] Lesson/video player
- [ ] Student dashboard
- [ ] Payment gateway integration

## 🤝 Contributing

Contributions, issues and feature requests are welcome!
Fork the repo, create a branch, and open a pull request.

## 🇧🇩 বাংলায় সংক্ষেপে

**lessonLMS** একটি হালকা ও কাস্টম WordPress LMS থিম। কোনো ভারী প্লাগিন ছাড়াই
নিজের অনলাইন কোর্স ওয়েবসাইট বানানো যায়। কোর্স ম্যানেজমেন্ট, AJAX এনরোলমেন্ট,
রিভিউ ও রেটিং সিস্টেম এবং Customizer সাপোর্ট এতে আছে। বাংলাদেশি ডেভেলপার ও
শিক্ষার্থীদের WordPress থিম ডেভেলপমেন্ট শেখার জন্যও এটি একটি ভালো উদাহরণ।

## 📄 License

Distributed under the [MIT License](LICENSE).

## 📫 Author

**Md. Nayemur Rahman** — Founder and Lead Instructor, ProjuktiPlus Academy
📧 nayemspecial@gmail.com · 🔗 [LinkedIn](https://linkedin.com/in/nayemspecial)

⭐ If you find this project useful, please give it a star!