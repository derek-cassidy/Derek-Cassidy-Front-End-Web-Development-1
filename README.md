# Derek-Cassidy-Front-End-Web-Development-1
Git hub respository for Coimmunication history website with active links 
I have rewritten my HTML, script and CSS to include the bootsrap chanmges that I made. Below is the bootstrap code I used and wher it fitted into my HTML code etc.
Overall the main changes that bootstrap has made cam be seen with the changes made to the original webpages and the new webpages. 
In the new main webpage the display is different as it is now now in colums and also the links page is also different with links tpo actual third party sites.

Below is my original HTML code and the new code with bootstrap 


# Bootstrap Guide for Beginners

## What is Bootstrap?

Bootstrap is basically a big collection of pre-written CSS and JavaScript that makes building websites way easier. Instead of writing all your own CSS for buttons, navigation bars, grids, etc., you just use Bootstrap's classes and it does the work for you.

**Why bother with Bootstrap?**
- You save a ton of time not writing CSS from scratch
- Your site automatically works on phones, tablets, and desktops
- You get decent-looking components without being a design wizard

## How to Add Bootstrap to Your Site

### Step 1: Add the Links

You need two links in both `index.html` and `links.html`:

**In the `<head>` section (before your style.css):**
```html
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
```
This loads Bootstrap's CSS. The CDN thing just means we're loading it from the internet instead of downloading files.

**Before the closing `</body>` tag:**
```html
<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
```
This loads Bootstrap's JavaScript. You need this for things like the mobile menu to work.

## Bootstrap Components I Used

### 1. Navbar (Navigation Bar)

This is the menu at the top of your page.

**Before:**
```html
<header>
    <nav>
        <h1>Communication History</h1>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="links.html">Links</a></li>
        </ul>
    </nav>
</header>
```

**After:**
```html
<nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
        <a class="navbar-brand" href="index.html">
            <h1>Communication History</h1>
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link active" href="index.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="links.html">Links</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
```

**What the classes do:**
- `navbar` - tells Bootstrap this is a navbar
- `navbar-expand-lg` - collapses into a hamburger menu on small screens
- `navbar-dark` - white text (works with the purple background)
- `navbar-toggler` - that hamburger button for mobile
- `container` - centers everything and adds some padding
- `ms-auto` - pushes the nav links to the right side

### 2. Grid System (Layout)

This is probably the most useful part of Bootstrap. It divides your page into 12 columns and lets you decide how many columns each item takes up.

**Before:**
```html
<div class="timeline-item">
    <h3>Ancient Times</h3>
    <p>Content here...</p>
</div>
```

**After:**
```html
<div class="row">
    <div class="col-md-6 mb-4 d-flex">
        <div class="timeline-item">
            <h3>Ancient Times</h3>
            <p>Content here...</p>
        </div>
    </div>
</div>
```

**What the classes do:**
- `row` - creates a horizontal row that holds columns
- `col-md-6` - takes up 6 out of 12 columns (50% width) on medium screens and up
- `mb-4` - margin-bottom spacing
- `d-flex` - makes cards in the same row have equal height (so one card doesn't look taller than the other)

**How the grid math works:**
- Bootstrap uses 12 columns total
- `col-md-6` = 6/12 = 50% width = 2 cards per row
- `col-md-4` = 4/12 = 33% width = 3 cards per row
- `col-md-12` = 12/12 = 100% width = 1 card per row

The "md" part means it only kicks in on medium screens (tablets) and larger. On phones, everything stacks to full width automatically.

### 3. Container

```html
<div class="container">
    <!-- Your content goes here -->
</div>
```

**What it does:**
- Centers your content on the page
- Adds padding on the sides
- Stops content from stretching too wide on big screens (nobody wants to read text that goes across a 27" monitor)

### 4. Spacing Classes

Bootstrap has shorthand classes for adding margins and padding without writing custom CSS:

- `mb-4` = margin-bottom
- `mt-3` = margin-top
- `p-5` = padding all around
- `py-4` = padding top and bottom only
- `ms-auto` = margin-start auto (pushes stuff to the right)

The numbers go from 0 to 5 (0 = no space, 5 = lots of space)

## What Actually Changed in Your Code

### index.html:

1. **Navbar** - Added Bootstrap navbar classes so it collapses into a hamburger menu on phones
2. **Grid layout** - Wrapped cards in `row` and `col-md-6` classes so you get 2 cards per row on tablets/desktops, and they stack on phones
3. **Equal height cards** - Added `d-flex` so cards in the same row are the same height (looks way better)
4. **Container** - Wrapped everything in a container for proper centering and spacing
5. **Kept your styling** - All your purple gradient and custom colors still work since style.css loads after Bootstrap

### links.html:

1. **Same navbar** - Used the exact same Bootstrap navbar for consistency
2. **Grid layout** - Used `col-md-6` so link categories display 2 per row on tablets and up, single column on phones
3. **Equal heights** - Same `d-flex` trick so the cards match heights
4. **Kept all your styling** - Your link card styles still apply

## Important Bootstrap Stuff to Know

### Screen Size Breakpoints

Bootstrap changes your layout based on screen width. Here's what the abbreviations mean:

- `sm` = small (576px+) - phones in landscape
- `md` = medium (768px+) - tablets
- `lg` = large (992px+) - laptops
- `xl` = extra large (1200px+) - big desktops

So `col-md-6` means "on tablets and bigger, take up 6 columns. On phones, take up full width."

### Common Classes You'll Use

**Layout stuff:**
- `container` - centers and constrains content width
- `row` - holds columns
- `col-md-6` - column that's half width on medium screens and up
- `d-flex` - makes items in a row the same height

**Navbar stuff:**
- `navbar` - makes a navbar
- `navbar-brand` - your site name/logo
- `nav-link` - links in the navbar
- `navbar-toggler` - the mobile hamburger button

**Spacing shortcuts:**
- `mb-4` - margin bottom
- `mt-3` - margin top
- `p-5` - padding
- `ms-auto` - pushes to the right

**Text alignment:**
- `text-center` - center text
- `text-start` - left align
- `text-end` - right align

## Testing It Out

Try this to see Bootstrap working:

1. Open http://localhost:8000 in your browser
2. Drag the browser window to make it narrower
3. Watch the navbar collapse into a hamburger menu
4. Watch the cards stack vertically on narrow screens
5. Make it wider again and see cards go side-by-side

## Questions You Might Have

**Do I need to download Bootstrap files?**
Nope! The CDN links pull it from the internet. Easy.

**Will Bootstrap break my custom CSS?**
No. As long as style.css comes after the Bootstrap link, your styles win when there's a conflict.

**Do I have to memorize all these classes?**
Definitely not. Just keep the Bootstrap docs open: https://getbootstrap.com/docs/5.3/

**What's the most important thing?**
The grid system. Seriously, if you get how `row` and `col-*` work, you're good.

**Why does my CSS need to come after Bootstrap?**
CSS loads top to bottom. If your style.css comes after Bootstrap, your rules override Bootstrap's rules. It's called "specificity" but just remember: your CSS goes last.

## Quick Summary

We added:
- Bootstrap CSS and JS links
- Bootstrap navbar (with mobile menu)
- Bootstrap grid system (for responsive layout)
- Container for centering
- d-flex for equal height cards

We kept:
- All your purple gradient styling
- Your card designs
- Your colors
- Everything in style.css

Result: Site works on any device without writing a bunch of responsive CSS by hand.

## If You Get Stuck

- Bootstrap Docs: https://getbootstrap.com/docs/5.3/getting-started/introduction/
- Bootstrap Examples: https://getbootstrap.com/docs/5.3/examples/
- Look at the HTML comments in your code


