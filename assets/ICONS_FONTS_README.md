# Icons & Fonts Documentation

## Overview
This project uses Font Awesome icons and Google Fonts for a modern, professional look.

---

## Google Fonts

### Imported Fonts
- **Poppins** (weights: 300, 400, 500, 600, 700) - Used for modern headings and UI elements
- **Roboto** (weights: 400, 500, 700) - Used for body text and content

### How to Use Fonts

In your CSS:
```css
/* For Poppins font */
h1, h2, h3 {
    font-family: 'Poppins', sans-serif;
    font-weight: 600;
}

/* For Roboto font */
p, body {
    font-family: 'Roboto', sans-serif;
    font-weight: 400;
}
```

---

## Font Awesome Icons

### CDN Link
Font Awesome is loaded from CDN:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

### How to Use Icons

Basic syntax:
```html
<i class="fas fa-icon-name"></i>
```

### Common Icon Categories & Examples

#### Search & Navigation
| Icon Name | Usage | Code |
|-----------|-------|------|
| search | Search functionality | `<i class="fas fa-search"></i>` |
| bars | Menu hamburger | `<i class="fas fa-bars"></i>` |
| arrow-right | Next/Forward | `<i class="fas fa-arrow-right"></i>` |
| arrow-left | Previous/Back | `<i class="fas fa-arrow-left"></i>` |
| times | Close/Cancel | `<i class="fas fa-times"></i>` |
| home | Home page | `<i class="fas fa-home"></i>` |

#### Social Media
| Icon Name | Usage | Code |
|-----------|-------|------|
| facebook | Facebook | `<i class="fab fa-facebook"></i>` |
| twitter | Twitter | `<i class="fab fa-twitter"></i>` |
| linkedin | LinkedIn | `<i class="fab fa-linkedin"></i>` |
| github | GitHub | `<i class="fab fa-github"></i>` |
| instagram | Instagram | `<i class="fab fa-instagram"></i>` |
| youtube | YouTube | `<i class="fab fa-youtube"></i>` |

#### Business & Professional
| Icon Name | Usage | Code |
|-----------|-------|------|
| briefcase | Work/Jobs | `<i class="fas fa-briefcase"></i>` |
| user | User profile | `<i class="fas fa-user"></i>` |
| users | Team/People | `<i class="fas fa-users"></i>` |
| envelope | Email | `<i class="fas fa-envelope"></i>` |
| phone | Phone | `<i class="fas fa-phone"></i>` |
| map-marker | Location | `<i class="fas fa-map-marker-alt"></i>` |
| star | Rating/Favorite | `<i class="fas fa-star"></i>` |
| check | Success/Done | `<i class="fas fa-check"></i>` |

#### Design & Content
| Icon Name | Usage | Code |
|-----------|-------|------|
| image | Images/Gallery | `<i class="fas fa-image"></i>` |
| file | Document | `<i class="fas fa-file"></i>` |
| download | Download | `<i class="fas fa-download"></i>` |
| upload | Upload | `<i class="fas fa-upload"></i>` |
| edit | Edit/Pencil | `<i class="fas fa-edit"></i>` |
| trash | Delete | `<i class="fas fa-trash"></i>` |
| bell | Notifications | `<i class="fas fa-bell"></i>` |
| heart | Like/Favorite | `<i class="fas fa-heart"></i>` |

#### Finance & Commerce
| Icon Name | Usage | Code |
|-----------|-------|------|
| shopping-cart | Cart/Buy | `<i class="fas fa-shopping-cart"></i>` |
| credit-card | Payment | `<i class="fas fa-credit-card"></i>` |
| dollar-sign | Price | `<i class="fas fa-dollar-sign"></i>` |
| wallet | Wallet/Account | `<i class="fas fa-wallet"></i>` |
| chart-line | Analytics | `<i class="fas fa-chart-line"></i>` |

#### UI/UX
| Icon Name | Usage | Code |
|-----------|-------|------|
| cog | Settings | `<i class="fas fa-cog"></i>` |
| sliders | Filters | `<i class="fas fa-sliders-h"></i>` |
| info-circle | Information | `<i class="fas fa-info-circle"></i>` |
| exclamation | Warning | `<i class="fas fa-exclamation"></i>` |
| question-circle | Help/FAQ | `<i class="fas fa-question-circle"></i>` |
| spinner | Loading | `<i class="fas fa-spinner fa-spin"></i>` |

---

## Icon Sizes & Styling

### Size Variations
```html
<!-- Normal size -->
<i class="fas fa-search"></i>

<!-- Large size -->
<i class="fas fa-search fa-lg"></i>

<!-- Extra large -->
<i class="fas fa-search fa-2x"></i>
<i class="fas fa-search fa-3x"></i>
<i class="fas fa-search fa-4x"></i>
```

### Styling Examples
```html
<!-- Colored icons -->
<i class="fas fa-heart" style="color: red;"></i>

<!-- With animation -->
<i class="fas fa-spinner fa-spin"></i>

<!-- In buttons -->
<button class="btn">
    <i class="fas fa-download"></i> Download
</button>

<!-- Icon with text -->
<span>
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</span>
```

---

## CSS Icon Styling

Add these to your `style.css`:

```css
/* Icon button styling */
.icon-btn {
    background: none;
    border: none;
    cursor: pointer;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

.icon-btn:hover {
    color: #3498db;
}

/* Icon with text spacing */
.icon-text {
    display: flex;
    align-items: center;
    gap: 0.5rem;
}

/* Animated spinning icon */
.icon-spin {
    animation: spin 1s linear infinite;
}

@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}

/* Icon color variants */
.icon-primary {
    color: #3498db;
}

.icon-success {
    color: #2ecc71;
}

.icon-danger {
    color: #e74c3c;
}

.icon-warning {
    color: #f39c12;
}
```

---

## Practical Examples

### Navigation with Icons
```html
<nav>
    <a href="#home"><i class="fas fa-home"></i> Home</a>
    <a href="#about"><i class="fas fa-user"></i> About</a>
    <a href="#services"><i class="fas fa-briefcase"></i> Services</a>
    <a href="#contact"><i class="fas fa-envelope"></i> Contact</a>
</nav>
```

### Contact Section with Icons
```html
<div class="contact-info">
    <p><i class="fas fa-phone"></i> +1 (555) 123-4567</p>
    <p><i class="fas fa-envelope"></i> hello@example.com</p>
    <p><i class="fas fa-map-marker-alt"></i> 123 Main St, City, State</p>
</div>
```

### Social Media Links
```html
<div class="social-links">
    <a href="#"><i class="fab fa-facebook fa-2x"></i></a>
    <a href="#"><i class="fab fa-twitter fa-2x"></i></a>
    <a href="#"><i class="fab fa-linkedin fa-2x"></i></a>
    <a href="#"><i class="fab fa-github fa-2x"></i></a>
</div>
```

### Call-to-Action Button
```html
<button class="cta-btn">
    <i class="fas fa-arrow-right"></i> Get Started
</button>
```

---

## Icon Sets Used

- **fas** = Font Awesome Solid (filled icons)
- **far** = Font Awesome Regular (outline icons)
- **fab** = Font Awesome Brands (social media & brand icons)

Example:
```html
<i class="fas fa-heart"></i>  <!-- Solid heart -->
<i class="far fa-heart"></i>  <!-- Outline heart -->
```

---

## Resources

- **Font Awesome Official**: https://fontawesome.com/
- **Google Fonts**: https://fonts.google.com/
- **Icon Search**: https://fontawesome.com/search

---

## Notes

- Font Awesome v6.4.0 is loaded from CDN
- Google Fonts (Poppins & Roboto) are preloaded for better performance
- Always test icons across different browsers and devices
- Ensure sufficient color contrast for accessibility
