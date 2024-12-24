# Project Responsive Web Design using Bootstrap
# Date:24-11-2024
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
html code:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Dribbble Clone - Advanced Design</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <!-- Header Section -->
        <header class="p-3 text-white">
            <div class="container d-flex justify-content-between align-items-center">
                <h1 class="logo">Dribbble</h1>
                <nav>
                    <ul class="nav">
                        <li class="nav-item"><a href="#home" class="nav-link text-white"><i class="fas fa-home"></i> Home</a></li>
                        <li class="nav-item"><a href="#explore" class="nav-link text-white"><i class="fas fa-compass"></i> Explore</a></li>
                        <li class="nav-item"><a href="#about" class="nav-link text-white"><i class="fas fa-info-circle"></i> About</a></li>
                        <li class="nav-item"><a href="#contact" class="nav-link text-white"><i class="fas fa-envelope"></i> Contact</a></li>
                    </ul>
                </nav>
            </div>
        </header>
    
        <!-- Hero Section -->
        <section id="home" class="text-center py-5">
            <div class="container">
                <h1 class="display-4">Discover the World’s Top Designers</h1>
                <p class="lead">Explore work from the most talented and accomplished designers ready to take on your next project.</p>
                <input type="text" class="form-control my-3" placeholder="What are you looking for?" />
                <button class="btn btn-primary btn-lg">Search</button>
            </div>
        </section>
    
        <!-- Gallery Section -->
        <section id="explore" class="container my-5">
            <h2 class="text-center mb-4">Featured Designs</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image1.jpg" alt="Design 1">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image2.jpg" alt="Design 2">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image3.jpg" alt="Design 3">
                    </div>
                </div>
            </div>
            <div class="row mt-4">
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image4.jpg" alt="Design 4">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image5.jpg" alt="Design 5">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image6.jpg" alt="Design 6">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image7.jpg" alt="Design 6">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image8.jpg" alt="Design 6">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image9.jpg" alt="Design 6">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image10.jpg" alt="Design 6">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image11.jpg" alt="Design 6">
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="image-container">
                        <img src="images/image12.jpg" alt="Design 6">
                    </div>
                </div>
            </div>
        </section>
    
        <!-- About Section -->
        <section id="about" class="py-5 text-center">
            <div class="container">
                <h2>About Us</h2>
                <p class="lead">We connect you to the best designers worldwide. Whether you need mobile app design, branding, or product design, we’ve got you covered.</p>
            </div>
        </section>
    
        <!-- Contact Section -->
        <section id="contact" class="py-5 text-center">
            <div class="container">
                <h2>Contact Us</h2>
                <form>
                    <div class="mb-3">
                        <input type="text" class="form-control" placeholder="Your Name">
                    </div>
                    <div class="mb-3">
                        <input type="email" class="form-control" placeholder="Your Email">
                    </div>
                    <div class="mb-3">
                        <textarea class="form-control" rows="5" placeholder="Your Message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </section>
    
        <!-- Footer -->
        <footer class="text-center py-3">
            <p>&copy; 2024 Dribbble . All Rights Reserved.</p>
            <p>Follow us: 
                <a href="#" class="text-info"><i class="fab fa-facebook"></i></a>
                <a href="#" class="text-info"><i class="fab fa-twitter"></i></a>
                <a href="#" class="text-info"><i class="fab fa-instagram"></i></a>
            </p>
        </footer>
    </body>
    </html>

css code:

    body {
        font-family: 'Arial', sans-serif;
        background: linear-gradient(to bottom, #1a2a6c, #b21f1f, #fdbb2d);
        color: white;
        margin: 0;
        padding: 0;
    }
    
    header {
        background: linear-gradient(45deg, #141e30, #243b55);
        border-bottom: 2px solid #ff6f61;
    }
    
    .logo {
        font-size: 28px;
        font-weight: bold;
        color: #ff6f61;
    }
    
    #home {
        background: linear-gradient(to right, #000428, #004e92);
        padding: 60px 0;
    }
    
    .image-container {
        position: relative;
        overflow: hidden;
        transition: transform 0.3s;
        border-radius: 15px;
    }
    
    .image-container img {
        width: 100%;
        height: auto;
        transition: transform 0.3s ease;
    }
    
    .image-container:hover img {
        transform: scale(1.1);
        box-shadow: 0px 4px 20px rgba(255, 255, 255, 0.985);
    }
    
    #about, #contact {
        background: linear-gradient(90deg, #243b55, #141e30);
    }
    
    footer {
        background: linear-gradient(45deg, #232526, #414345);
        color: #fff;
    }
    
    footer a {
        margin: 0 10px;
        color: #ff6f61;
    }
    
    footer a:hover {
        color: #ff9a8c;
    }

javascript code:


    document.addEventListener('DOMContentLoaded', () => {
        const imageContainer = document.getElementById('image-container');
        const imageCount = 10;
    
        // Dynamically generate image elements
        const createImageElement = (src, altText) => {
            const divElement = document.createElement('div');
            divElement.className = 'col-md-4 col-sm-6 mb-4'; // Responsive grid classes
    
            const imgElement = document.createElement('img');
            imgElement.src = src;
            imgElement.alt = altText;
            imgElement.className = 'img-fluid rounded shadow lazy-load';
            imgElement.loading = 'lazy'; // Lazy loading attribute for performance
    
            // Add error handling if image fails to load
            imgElement.onerror = () => {
                imgElement.src = 'images/placeholder.jpg'; // Fallback image
                imgElement.alt = 'Placeholder Image';
            };
    
            divElement.appendChild(imgElement);
            return divElement;
        };
    
        // Simulating fetching data (e.g., from an API)
        const fetchImages = () => {
            return new Promise((resolve) => {
                const imageList = [];
                for (let i = 1; i <= imageCount; i++) {
                    imageList.push({
                        src: `images/img${i}.jpg`,
                        alt: `Sample Image ${i}`,
                    });
                }
                setTimeout(() => resolve(imageList), 1000); // Simulate API delay
            });
        };
    
        // Populate the image container
        const populateImages = async () => {
            try {
                const images = await fetchImages();
                images.forEach(({ src, alt }) => {
                    const imageElement = createImageElement(src, alt);
                    imageContainer.appendChild(imageElement);
                });
            } catch (error) {
                console.error('Error loading images:', error);
            }
        };
    
        // Execute the function to populate images
        populateImages();
    });
    

# OUTPUT:

![image](https://github.com/user-attachments/assets/3a5d23ec-b1ba-4102-b3ed-01063f4ca2a2)
![image](https://github.com/user-attachments/assets/3495bc8c-9d96-40a6-89b1-b1e86e2b74f8)
![image](https://github.com/user-attachments/assets/5e584c13-cdbd-4563-b6c2-d012ffddcf10)
![image](https://github.com/user-attachments/assets/c0ab91a6-610c-49bc-820d-262688487b97)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
