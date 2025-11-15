# Derek-Cassidy-Front-End-Web-Development-1
Git hub respository for Coimmunication history website with active links 
I have rewritten my HTML, script and CSS to include the bootsrap chanmges that I made. Below is the bootstrap code I used and wher it fitted into my HTML code etc.
Overall the main changes that bootstrap has made cam be seen with the changes made to the original webpages and the new webpages. 
In the new main webpage the display is different as it is now now in colums and also the links page is also different with links tpo actual third party sites.

Below is my original HTML code and the new code with bootstrap 

New index.html code with bootstrap
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Communication History - Home</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Bootstrap Navbar Component -->
    <header>
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
    </header>

    <!-- Bootstrap Container for spacing -->
    <main>
        <div class="container">
            <!-- Hero Section -->
            <section class="hero">
                <h2>Welcome to Communication History</h2>
                <p>Explore the fascinating evolution of human communication through the ages</p>
            </section>

            <!-- Bootstrap Grid System -->
            <section class="content">
                <div class="row">
                    <!-- Bootstrap Card 1 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="timeline-item">
                            <h3>Ancient Times</h3>
                            <p>From cave paintings to smoke signals, early humans found creative ways to share information across distances. These primitive methods laid the foundation for all future communication technologies.</p>
                        </div>
                    </div>

                    <!-- Bootstrap Card 2 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="timeline-item">
                            <h3>Written Language</h3>
                            <p>The development of writing systems revolutionized how we preserve and transmit knowledge. From hieroglyphs to alphabets, written communication became the backbone of civilization.</p>
                        </div>
                    </div>

                    <!-- Bootstrap Card 3 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="timeline-item">
                            <h3>Printing Press</h3>
                            <p>Gutenberg's invention in the 15th century democratized information, making books and knowledge accessible to the masses for the first time in history.</p>
                        </div>
                    </div>

                    <!-- Bootstrap Card 4 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="timeline-item">
                            <h3>Telegraph & Telephone</h3>
                            <p>The 19th century brought instant long-distance communication. Messages could now travel faster than any horse or ship, connecting the world like never before.</p>
                        </div>
                    </div>

                    <!-- Bootstrap Card 5 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="timeline-item">
                            <h3>Radio & Television</h3>
                            <p>Broadcasting technology brought news, entertainment, and education directly into people's homes, creating shared cultural experiences across vast populations.</p>
                        </div>
                    </div>

                    <!-- Bootstrap Card 6 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="timeline-item">
                            <h3>Internet Age</h3>
                            <p>The digital revolution transformed communication once again. Email, social media, and instant messaging have made global communication instantaneous and accessible to billions.</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Call to Action with Bootstrap Button -->
            <section class="cta">
                <h3>Explore More</h3>
                <p>Ready to dive deeper into communication history? Check out our curated collection of resources and external links.</p>
                <a href="links.html" class="btn">View Links</a>
            </section>
        </div>
    </main>

    <footer>
        <p>&copy; 2025 Communication History Project</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>

New links.html code 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Communication History - Links</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Bootstrap Navbar Component -->
    <header>
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
                            <a class="nav-link" href="index.html">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link active" href="links.html">Links</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <main>
        <div class="container">
            <!-- Hero Section -->
            <section class="hero">
                <h2>Useful Resources</h2>
                <p>Explore these carefully selected websites to learn more about communication history</p>
            </section>

            <!-- Bootstrap Grid for Links -->
            <section class="links-grid">
                <div class="row">
                    <!-- Column 1 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="link-category">
                            <h3>Museums & Exhibits</h3>
                            <div class="link-item">
                                <h4>Smithsonian National Museum of American History</h4>
                                <p>Explore exhibits on the history of communication technology</p>
                                <a href="https://americanhistory.si.edu/" target="_blank" class="external-link">Visit Site</a>
                            </div>
                            <div class="link-item">
                                <h4>Computer History Museum</h4>
                                <p>Learn about the digital revolution and early computing</p>
                                <a href="https://computerhistory.org/" target="_blank" class="external-link">Visit Site</a>
                            </div>
                        </div>
                    </div>

                    <!-- Column 2 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="link-category">
                            <h3>Educational Resources</h3>
                            <div class="link-item">
                                <h4>History of Communication - Britannica</h4>
                                <p>Comprehensive encyclopedia entries on communication history</p>
                                <a href="https://www.britannica.com/topic/communication" target="_blank" class="external-link">Visit Site</a>
                            </div>
                            <div class="link-item">
                                <h4>Khan Academy - World History</h4>
                                <p>Free courses covering the development of human communication</p>
                                <a href="https://www.khanacademy.org/humanities/world-history" target="_blank" class="external-link">Visit Site</a>
                            </div>
                        </div>
                    </div>

                    <!-- Column 3 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="link-category">
                            <h3>Technology History</h3>
                            <div class="link-item">
                                <h4>Internet Society</h4>
                                <p>Learn about the history and development of the internet</p>
                                <a href="https://www.internetsociety.org/internet/history-internet/" target="_blank" class="external-link">Visit Site</a>
                            </div>
                            <div class="link-item">
                                <h4>Telephone History</h4>
                                <p>Detailed timeline of telephone technology development</p>
                                <a href="https://www.history.com/topics/inventions/telephone" target="_blank" class="external-link">Visit Site</a>
                            </div>
                        </div>
                    </div>

                    <!-- Column 4 -->
                    <div class="col-md-6 mb-4 d-flex">
                        <div class="link-category">
                            <h3>Academic Sources</h3>
                            <div class="link-item">
                                <h4>MIT Technology Review</h4>
                                <p>Articles on the evolution of communication technology</p>
                                <a href="https://www.technologyreview.com/" target="_blank" class="external-link">Visit Site</a>
                            </div>
                            <div class="link-item">
                                <h4>IEEE Computer Society</h4>
                                <p>Technical papers on computing and communication history</p>
                                <a href="https://www.computer.org/" target="_blank" class="external-link">Visit Site</a>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Back Button -->
            <section class="back-home">
                <a href="index.html" class="btn">Back to Home</a>
            </section>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Communication History Project</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>

New script.jc code with bootstrap
document.addEventListener('DOMContentLoaded', function() {
    
    // Add smooth scrolling for internal links
    const internalLinks = document.querySelectorAll('a[href^="#"]');
    internalLinks.forEach(link => {
        link.addEventListener('click', function(e) {
            e.preventDefault();
            const target = document.querySelector(this.getAttribute('href'));
            if (target) {
                target.scrollIntoView({
                    behavior: 'smooth'
                });
            }
        });
    });

    // Add animation to timeline items on scroll
    const timelineItems = document.querySelectorAll('.timeline-item');
    
    function animateOnScroll() {
        timelineItems.forEach(item => {
            const itemTop = item.getBoundingClientRect().top;
            const itemVisible = 150;
            
            if (itemTop < window.innerHeight - itemVisible) {
                item.style.opacity = '1';
                item.style.transform = 'translateY(0)';
            }
        });
    }

    // Initialize timeline items as hidden
    timelineItems.forEach(item => {
        item.style.opacity = '0';
        item.style.transform = 'translateY(30px)';
        item.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    });

    // Listen for scroll events
    window.addEventListener('scroll', animateOnScroll);
    
    // Run once on load
    animateOnScroll();

    // Add click tracking for external links
    const externalLinks = document.querySelectorAll('.external-link');
    externalLinks.forEach(link => {
        link.addEventListener('click', function() {
            console.log('External link clicked:', this.href);
        });
    });

    // Add a simple welcome message
    console.log('Welcome to Communication History!');
    
    // Simple page load animation
    document.body.style.opacity = '0';
    document.body.style.transition = 'opacity 0.5s ease';
    
    setTimeout(() => {
        document.body.style.opacity = '1';
    }, 100);

});

New style.css code with bootstrap
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 1rem 0;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

nav {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav h1 {
    font-size: 1.8rem;
}

nav ul {
    display: flex;
    list-style: none;
    gap: 2rem;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    transition: background-color 0.3s;
}

nav a:hover,
nav a.active {
    background-color: rgba(255,255,255,0.2);
}

main {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
}

.hero {
    text-align: center;
    background: white;
    padding: 3rem 2rem;
    border-radius: 10px;
    margin-bottom: 2rem;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #667eea;
}

.hero p {
    font-size: 1.2rem;
    color: #666;
}

.content {
    display: grid;
    gap: 2rem;
    margin-bottom: 3rem;
}

.timeline-item {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    border-left: 4px solid #667eea;
    transition: transform 0.3s;
    width: 100%;
}

.timeline-item:hover {
    transform: translateY(-5px);
}

.timeline-item h3 {
    color: #667eea;
    margin-bottom: 1rem;
    font-size: 1.5rem;
}

.links-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-bottom: 3rem;
}

.link-category {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    width: 100%;
}

.link-category h3 {
    color: #667eea;
    margin-bottom: 1.5rem;
    font-size: 1.5rem;
    border-bottom: 2px solid #667eea;
    padding-bottom: 0.5rem;
}

.link-item {
    margin-bottom: 1.5rem;
    padding: 1rem;
    border: 1px solid #eee;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.link-item:hover {
    background-color: #f9f9f9;
}

.link-item h4 {
    color: #333;
    margin-bottom: 0.5rem;
}

.link-item p {
    color: #666;
    margin-bottom: 1rem;
    font-size: 0.9rem;
}

.external-link {
    display: inline-block;
    background: #667eea;
    color: white;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 5px;
    font-size: 0.9rem;
    transition: background-color 0.3s;
}

.external-link:hover {
    background: #5a6fd8;
}

.cta,
.back-home {
    text-align: center;
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.btn {
    display: inline-block;
    background: #667eea;
    color: white;
    padding: 1rem 2rem;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.1rem;
    margin-top: 1rem;
    transition: background-color 0.3s;
}

.btn:hover {
    background: #5a6fd8;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 2rem;
    margin-top: 3rem;
}

@media (max-width: 768px) {
    nav {
        flex-direction: column;
        gap: 1rem;
    }
    
    .hero h2 {
        font-size: 2rem;
    }
    
    main {
        padding: 1rem;
    }
    
    .links-grid {
        grid-template-columns: 1fr;
    }
}

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


