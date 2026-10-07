# 📝 DGA Sign-Up Form

A responsive authentication UI built with HTML and CSS, with lightweight JavaScript validation for password confirmation, password visibility toggles, and Nigerian phone number formatting.

This project is a frontend demonstration. It does not connect to a backend, create real accounts, or store submitted user data.

## ✨ Features

- **Responsive layout:** Two-panel desktop layout that adapts to smaller screens.
- **User details form:** Collects first name, last name, email address, phone number, password, and password confirmation.
- **Native form validation:** Uses required fields, input patterns, minimum lengths, maximum lengths, and email validation.
- **Password confirmation:** Provides live feedback when passwords match or differ and blocks submission when they do not match.
- **Password visibility toggles:** Show or hide both password fields with the eye icons.
- **Phone number formatting:** Keeps the phone field in the `+234 XXX XXX XXXX` format.
- **Success page:** Redirects valid submissions to a thank-you page.
- **Mobile-friendly styling:** Stacks the image and form panels on screens below 768px.
- **Social links:** Includes links to the author's professional and social profiles.

## 🛠️ Built with

- **HTML5** for semantic structure, form controls, and browser validation
- **CSS3** for the split-screen layout, responsive behavior, visual theme, and form states
- **JavaScript** for password validation, visibility toggles, phone formatting, and dynamic footer years
- **Font Awesome** for interface and social icons

## 🚀 Getting started

### Prerequisites

You only need a modern web browser. No build tools, package manager, backend, or database is required.

### Run locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/david-godspower/dga-sign-up-form.git
   ```

2. **Open the project directory**

   ```bash
   cd dga-sign-up-form
   ```

3. **Launch the form**

   Open `index.html` directly in your browser, or use the **Live Server** extension in VS Code.

## 🎯 How to use

1. Enter a first name and last name using letters and spaces.
2. Enter a valid email address.
3. Enter a Nigerian phone number beginning with `+234`.
4. Create a password between 8 and 15 characters.
5. Confirm the password.
6. Use the eye icons to show or hide password values.
7. Click **Create Account** after all fields pass validation.
8. The form redirects to `thankyou.html` after a valid submission.

## ✅ Validation rules

| Field | Requirement |
|---|---|
| First name | Required, at least 3 characters, letters and spaces |
| Last name | Required, at least 3 characters, letters and spaces |
| Email | Required, valid email format |
| Phone number | Required, `+234` followed by 10 digits |
| Password | Required, between 8 and 15 characters |
| Confirm password | Required and must match the password |

## 📁 Project structure

```text
dga-sign-up-form/
├── index.html       # Responsive sign-up form and inline validation logic
├── thankyou.html    # Successful submission confirmation page
├── style.css        # Form layout, responsive styles, and visual states
├── img/
│   ├── bg.png       # Form background image
│   ├── eye-icon.jpg # Eye icon asset
│   ├── lg.png       # Main logo
│   └── logo.png     # Additional logo asset
├── LICENSE          # MIT license
└── README.md        # Project documentation
```

## 🔐 Security and privacy

This is a frontend-only demonstration:

- Form values are not sent to a server.
- Passwords are not stored or transmitted by the project.
- The success page does not represent real account creation.
- A production authentication flow would require a secure backend, HTTPS, server-side validation, password hashing, CSRF protection, and secure session management.

Font Awesome is loaded from cdnjs, so an internet connection is required for the icons to appear.

## 👤 Author

**David Godspower Ajala**

- [GitHub](https://github.com/david-godspower)
- [Portfolio](https://david-godspower.github.io/david-portfolio/)
- [LinkedIn](https://www.linkedin.com/in/david-godspower-ajala/)
- [Facebook](https://facebook.com/DavidGodspowerAjalaDGA/)
- [Twitter/X](https://x.com/DavidGAjala)
- [Email](mailto:ajaladavid11@gmail.com)

## 📄 License

This project is available under the [MIT License](LICENSE).
