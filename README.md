
# Website Templates with W3.CSS and Tailwind CSS

This repository contains 10 different website templates built using **W3.CSS** and **Tailwind CSS**. Each template demonstrates a variety of layout designs and functionality, which can be easily customized for various types of projects.

## Templates Overview

### 1. **Landing Page (W3.CSS)**

A simple, clean landing page with a hero section, features, and footer.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <title>Landing Page</title>
</head>
<body class="w3-light-grey">

  <div class="w3-container w3-blue w3-center w3-padding-64">
    <h1>Welcome to Our Website</h1>
    <p>We are here to help you grow your business</p>
    <button class="w3-button w3-large w3-white w3-border w3-border-blue w3-round-large">Get Started</button>
  </div>

  <footer class="w3-container w3-blue w3-center w3-padding-32">
    <p>Contact us: info@example.com</p>
  </footer>

</body>
</html>
```

### 2. **Card Layout (Tailwind CSS)**

A card-based layout for showcasing services or products.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
  <title>Card Layout</title>
</head>
<body class="bg-gray-100">

  <div class="max-w-4xl mx-auto py-12 px-6">
    <h2 class="text-3xl font-semibold text-center text-gray-800 mb-12">Our Services</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
      <div class="bg-white p-6 rounded-lg shadow-md">
        <h3 class="text-2xl font-semibold text-gray-800">Service 1</h3>
        <p class="text-gray-600">Description of service 1.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow-md">
        <h3 class="text-2xl font-semibold text-gray-800">Service 2</h3>
        <p class="text-gray-600">Description of service 2.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow-md">
        <h3 class="text-2xl font-semibold text-gray-800">Service 3</h3>
        <p class="text-gray-600">Description of service 3.</p>
      </div>
    </div>
  </div>

</body>
</html>
```

### 3. **Contact Form (W3.CSS)**

A basic contact form with fields for name, email, and message.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <title>Contact Form</title>
</head>
<body>

  <div class="w3-container w3-padding-32">
    <h2 class="w3-center">Contact Us</h2>
    <form class="w3-container w3-card-4 w3-light-grey w3-padding-32">
      <label>Name</label>
      <input type="text" class="w3-input w3-border w3-margin-bottom" required>
      <label>Email</label>
      <input type="email" class="w3-input w3-border w3-margin-bottom" required>
      <label>Message</label>
      <textarea class="w3-input w3-border w3-margin-bottom" required></textarea>
      <button type="submit" class="w3-button w3-blue w3-round">Submit</button>
    </form>
  </div>

</body>
</html>
```

### 4. **Simple Navigation Bar (Tailwind CSS)**

A basic responsive navigation bar for website headers.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
  <title>Navigation Bar</title>
</head>
<body>

  <nav class="bg-blue-600 p-4">
    <ul class="flex space-x-6 text-white">
      <li><a href="#" class="hover:text-gray-200">Home</a></li>
      <li><a href="#about" class="hover:text-gray-200">About</a></li>
      <li><a href="#services" class="hover:text-gray-200">Services</a></li>
      <li><a href="#contact" class="hover:text-gray-200">Contact</a></li>
    </ul>
  </nav>

</body>
</html>
```

### 5. **Portfolio Layout (W3.CSS)**

A portfolio-style layout to display your work or projects.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <title>Portfolio Layout</title>
</head>
<body>

  <div class="w3-container w3-padding-32">
    <h2 class="w3-center">My Portfolio</h2>
    <div class="w3-row">
      <div class="w3-col l4 m6 s12 w3-padding-16">
        <div class="w3-card-4">
          <img src="https://via.placeholder.com/300" alt="Project 1" class="w3-image">
          <div class="w3-container">
            <h3>Project 1</h3>
            <p>Project description here.</p>
          </div>
        </div>
      </div>
      <div class="w3-col l4 m6 s12 w3-padding-16">
        <div class="w3-card-4">
          <img src="https://via.placeholder.com/300" alt="Project 2" class="w3-image">
          <div class="w3-container">
            <h3>Project 2</h3>
            <p>Project description here.</p>
          </div>
        </div>
      </div>
      <div class="w3-col l4 m6 s12 w3-padding-16">
        <div class="w3-card-4">
          <img src="https://via.placeholder.com/300" alt="Project 3" class="w3-image">
          <div class="w3-container">
            <h3>Project 3</h3>
            <p>Project description here.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

</body>
</html>
```

### 6. **Hero Section with Call-to-Action (Tailwind CSS)**

A hero section with a background image and a prominent CTA button.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
  <title>Hero Section</title>
</head>
<body>

  <section class="relative bg-blue-600 text-white h-screen">
    <div class="absolute inset-0 bg-black opacity-50"></div>
    <div class="relative z-10 flex items-center justify-center h-full">
      <div class="text-center px-6 md:px-12">
        <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6">Welcome to Our Website</h1>
        <p class="text-xl mb-8">Transforming your business through innovation</p>
        <a href="#services" class="bg-white text-blue-600 py-3 px-6 rounded-full text-xl hover:bg-gray-200">Get Started</a>
      </div>
    </div>
  </section>

</body>
</html>
```

### 7. **Footer Layout (W3.CSS)**

A footer layout with social media links and a contact email.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <title>

Footer Layout</title>
</head>
<body>

  <footer class="w3-container w3-blue w3-center w3-padding-32">
    <p>Follow us:</p>
    <a href="#" class="w3-button w3-circle w3-small w3-white w3-margin-right">FB</a>
    <a href="#" class="w3-button w3-circle w3-small w3-white w3-margin-right">TW</a>
    <a href="#" class="w3-button w3-circle w3-small w3-white">IG</a>
    <p>Contact us: info@example.com</p>
  </footer>

</body>
</html>
```

### 8. **Simple Blog Layout (Tailwind CSS)**

A blog-style layout to display posts with titles and descriptions.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
  <title>Simple Blog Layout</title>
</head>
<body class="bg-gray-100">

  <div class="max-w-4xl mx-auto py-12 px-6">
    <h2 class="text-3xl font-semibold text-center text-gray-800 mb-12">Blog</h2>
    <div class="space-y-12">
      <article class="bg-white p-6 rounded-lg shadow-md">
        <h3 class="text-2xl font-semibold text-gray-800">Blog Post Title</h3>
        <p class="text-gray-600">Blog post description goes here.</p>
      </article>
      <article class="bg-white p-6 rounded-lg shadow-md">
        <h3 class="text-2xl font-semibold text-gray-800">Blog Post Title</h3>
        <p class="text-gray-600">Blog post description goes here.</p>
      </article>
    </div>
  </div>

</body>
</html>
```

### 9. **Sidebar Layout (W3.CSS)**

A layout with a sidebar menu and a main content area.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <title>Sidebar Layout</title>
</head>
<body>

  <div class="w3-sidebar w3-light-grey w3-bar-block" style="width:250px;">
    <h3 class="w3-bar-item">Menu</h3>
    <a href="#" class="w3-bar-item w3-button">Home</a>
    <a href="#" class="w3-bar-item w3-button">About</a>
    <a href="#" class="w3-bar-item w3-button">Services</a>
  </div>

  <div style="margin-left:260px; padding:20px;">
    <h1>Main Content</h1>
    <p>This is the main content area.</p>
  </div>

</body>
</html>
```

### 10. **Product Display Grid (Tailwind CSS)**

A grid layout for showcasing products with images and descriptions.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
  <title>Product Display Grid</title>
</head>
<body>

  <div class="max-w-4xl mx-auto py-12 px-6">
    <h2 class="text-3xl font-semibold text-center text-gray-800 mb-12">Our Products</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
      <div class="bg-white p-6 rounded-lg shadow-md">
        <img src="https://via.placeholder.com/300" alt="Product 1" class="w-full h-48 object-cover rounded-lg mb-4">
        <h3 class="text-2xl font-semibold text-gray-800">Product 1</h3>
        <p class="text-gray-600">Product description goes here.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow-md">
        <img src="https://via.placeholder.com/300" alt="Product 2" class="w-full h-48 object-cover rounded-lg mb-4">
        <h3 class="text-2xl font-semibold text-gray-800">Product 2</h3>
        <p class="text-gray-600">Product description goes here.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow-md">
        <img src="https://via.placeholder.com/300" alt="Product 3" class="w-full h-48 object-cover rounded-lg mb-4">
        <h3 class="text-2xl font-semibold text-gray-800">Product 3</h3>
        <p class="text-gray-600">Product description goes here.</p>
      </div>
    </div>
  </div>

</body>
</html>
```

---

## Installation

To use these templates, simply clone or download this repository to your local machine:

```bash
git clone https://github.com/Olamify/Sample-Code-for-Websites.git
```

Then, open the individual HTML files in your browser to view the templates.

---

## Usage

Each template is designed to be easily customizable. You can update the content, change the colors, and adjust the layout as needed by modifying the HTML and CSS. 

- **W3.CSS** is used in the templates to quickly create responsive layouts with minimal code.
- **Tailwind CSS** is used in other templates to leverage utility-first classes to rapidly customize and build responsive designs.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Attributions

- **W3.CSS**: [W3Schools](https://www.w3schools.com/w3css/), a simple and responsive CSS framework for building websites.
- **Tailwind CSS**: [Tailwind CSS](https://tailwindcss.com/), a utility-first CSS framework for rapidly building custom user interfaces.
- **Font Awesome**: [Font Awesome](https://fontawesome.com/), for the icons used in some templates.

---

## Contributing

Contributions to improve these templates are welcome! Feel free to fork the repository, create a branch, and submit a pull request with your improvements or bug fixes.

### Steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push to your forked repository (`git push origin feature-name`).
5. Open a pull request on the original repository.

---

## Description of Templates

---

**Landing Page (W3.CSS)**:  
This template provides a clean and simple landing page with a hero section, features, and footer, ideal for introducing your brand or service.

**Card Layout (Tailwind CSS)**:  
A modern card-based layout used to display services, products, or features in an engaging, grid-style format.

**Contact Form (W3.CSS)**:  
A form template to collect contact information, such as name, email, and message, with a clean and simple design.

**Simple Navigation Bar (Tailwind CSS)**:  
A responsive navigation bar suitable for most websites. The design adapts well to mobile devices and offers easy customization.

**Portfolio Layout (W3.CSS)**:  
This layout is perfect for showcasing your projects or work, with a clean grid that supports images and descriptions.

**Hero Section with Call-to-Action (Tailwind CSS)**:  
A full-width hero section with a background image, offering a powerful visual and a call-to-action button to convert visitors.

**Footer Layout (W3.CSS)**:  
A simple footer that includes social media links and a contact email, ideal for most websites to provide additional contact information.

**Simple Blog Layout (Tailwind CSS)**:  
A modern blog layout with large, readable fonts and a clean, minimalistic design for posting articles or updates.

**Sidebar Layout (W3.CSS)**:  
A classic sidebar layout that allows for side navigation while leaving ample space for main content. Great for content-heavy websites.

**Product Display Grid (Tailwind CSS)**:  
A grid layout perfect for displaying products with images and descriptions, perfect for eCommerce websites.

---

Feel free to use, modify, and share these templates as per your project requirements!
