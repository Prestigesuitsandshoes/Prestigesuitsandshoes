/* General styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Header */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

/* Hero Section */
.hero {
    background: url('hero-image.jpg') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.hero-text {
    color: white;
    text-align: center;
}

.hero .btn {
    background-color: #FF5A5F;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 10px;
}

/* Product Section */
.products {
    padding: 20px;
    text-align: center;
}

.product-gallery {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.product-card {
    width: 300px;
    border: 1px solid #ccc;
    padding: 10px;
    margin: 20px;
    border-radius: 10px;
}

.product-card img {
    width: 100%;
}

.product-card button {
    background-color: #333;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
}

.product-card button:hover {
    background-color: #FF5A5F;
}

/* Reviews Section */
.reviews {
    margin-top: 20px;
    text-align: left;
}

.reviews h4 {
    color: #333;
    margin-bottom: 10px;
}

.reviews ul {
    list-style-type: none;
    padding: 0;
}

.reviews ul li {
    margin-bottom: 10px;
}

.reviews ul li strong {
    font-weight: bold;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
