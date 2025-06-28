# Project: Personal Profile Page Template

## 1. Overview & Purpose

This project provides a ready-to-use HTML template for creating a personal profile page. It is designed for members of the **Tbilisi Hack Club** to quickly set up a web presence on the `tbilisi.hackclub.com` domain.

| | |
| :--- | :--- |
| **Objective** | To provide a simple, customizable, and responsive personal webpage. |
| **Technology** | `HTML`, `Tailwind CSS` (via CDN), `Google Fonts` |
| **Intended User** | Members of the Tbilisi Hack Club. |

---

## 2. Visual Preview

The template features a clean, two-column layout on larger screens that adapts to a single column on mobile devices. The final appearance will reflect your personal information.

![Template Preview](https://i.imgur.com/sGXu2WR.png)


---

## 3. Features & Functionality

| Feature | Description |
| :--- | :--- |
| **Responsive Design** | Ensures the page looks great on all screen sizes, from mobile phones to desktops. |
| **Utility-First CSS** | Uses **Tailwind CSS** loaded from a CDN, meaning no installation or build process is required. |
| **Modern Typography** | Pre-configured with 'Manrope' and 'Noto Sans' from Google Fonts for excellent readability. |
| **Easy Customization**| All editable sections are clearly marked with placeholders like `NAME`, `ROLE`, and `avatar.png`. |
| **Branded Footer** | Contains permanent links to key Tbilisi Hack Club pages (Privacy, Terms, Contact) to maintain consistency. |

---

## 4. Setup and Customization Instructions

Follow these steps to personalize your page. You will only need to edit the `index.html` file.

| Step | Action | Code Snippet to Edit |
| :--- | :--- | :--- |
| **1. Page Title** | Change the text that appears in the browser tab. | `<title>CHANGE THIS</title>` |
| **2. Profile Picture**| Replace `"avatar.png"` with a URL to your photo. | `style="background-image: url('avatar.png');"` |
| **3. Your Name** | Update the main heading with your full name. | `<h1>NAME</h1>` |
| **4. Your Role** | Set your role within the club (e.g., Member, Leader). | `<p class="text-lg text-indigo-600">ROLE</p>` |
| **5. Join Year** | Change the year you joined Hack Club. | `<p class="mt-1 text-sm text-slate-500">Joined in 2025</p>` |
| **6. Biography** | Write your personal bio in this section. | `<p>some description and bio</p>` |

#### Example: Changing Your Name

**Before:**
```html
<h1 class="text-3xl font-bold text-slate-900">
    NAME
</h1>
````

**After:**

```html
<h1 class="text-3xl font-bold text-slate-900">
    Your Actual Name
</h1>
```

-----

## 5. Important Notes

  * The **footer** section at the bottom of the page is standardized and should not be modified. This ensures all member pages link back to important club resources.
    ```html
    <footer class="mt-8 text-center text-slate-500">
        <div
            class="flex flex-wrap items-center justify-center gap-6"
        >
            <a
                class="hover:text-slate-900"
                href="[https://tbilisi.hackclub.com/privacy-policy](https://tbilisi.hackclub.com/privacy-policy)"
                >Privacy Policy</a
            >
            <a
                class="hover:text-slate-900"
                href="[https://tbilisi.hackclub.com/terms-and-conditions](https://tbilisi.hackclub.com/terms-and-conditions)"
                >Terms of Service</a
            >
            <a
                class="hover:text-slate-900"
                href="[https://tbilisi.hackclub.com/contact](https://tbilisi.hackclub.com/contact)"
                >Contact Us</a
            >
        </div>
        <p class="mt-4 text-sm">
            ©2025 Tbilisi Hack Club. All rights reserved.
        </p>
    </footer>
    ```
  * This template is designed to be a single, self-contained HTML file for simplicity.
