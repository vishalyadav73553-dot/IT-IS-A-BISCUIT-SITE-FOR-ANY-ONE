<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Namkeen & Sweets Delight</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { font-family: Arial, sans-serif; }
        .hero { background: url('https://via.placeholder.com/1920x600?text=Namkeen+and+Sweets') no-repeat center; background-size: cover; height: 400px; color: white; display: flex; align-items: center; justify-content: center; text-align: center; }
        .product-card { margin: 20px; }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Namkeen & Sweets Delight</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section id="home" class="hero">
        <div>
            <h1>Welcome to Namkeen & Sweets Delight</h1>
            <p>Authentic Indian namkeen and mouth-watering sweets delivered fresh!</p>
            <a href="#products" class="btn btn-primary">Explore Products</a>
        </div>
    </section>

    <section id="products" class="container my-5">
        <h2 class="text-center mb-4">Our Products</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="https://via.placeholder.com/300x200?text=Namkeen" class="card-img-top" alt="Namkeen">
                    <div class="card-body">
                        <h5 class="card-title">Savory Namkeen</h5>
                        <p class="card-text">Crispy snacks like sev, khakra, and more. Perfect for munching!</p>
                        <p class="text-success">$5.99 per pack</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="https://via.placeholder.com/300x200?text=Sweets" class="card-img-top" alt="Sweets">
                    <div class="card-body">
                        <h5 class="card-title">Traditional Sweets</h5>
                        <p class="card-text">Gulab jamun, laddoos, and barfis made with love.</p>
                        <p class="text-success">$7.99 per box</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="https://via.placeholder.com/300x200?text=Combo" class="card-img-top" alt="Combo">
                    <div class="card-body">
                        <h5 class="card-title">Namkeen & Sweets Combo</h5>
                        <p class="card-text">Best of both worlds in one package.</p>
                        <p class="text-success">$12.99</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">About Us</h2>
            <p class="text-center">We specialize in authentic Indian namkeen and sweets, using traditional recipes and fresh ingredients. Established in 2020, we're committed to quality and customer satisfaction.</p>
        </div>
    </section>

    <section id="contact" class="container my-5">
        <h2 class="text-center mb-4">Contact Us</h2>
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email">
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Message</label>
                <textarea class="form-control" id="message" rows="3"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send</button>
        </form>
        <p class="mt-3">Phone: +1-123-456-7890 | Email: info@namkeensweets.com</p>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2023 Namkeen & Sweets Delight. All rights reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
