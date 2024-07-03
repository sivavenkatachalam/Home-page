<!DOCTYPE html>
<html lang="en">
<head>
   
    <title>Fullstack Task</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f0f0f0;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #3c3295;
            color: white;
            padding: 10px 20px;
        }
        header .logo {
            font-size: 1.2em;
        }
        nav ul {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        nav ul li a:hover {
            color: #f1c40f;
        }
        .main {
            background-color: #f9ca24;
            padding: 50px;
            text-align: center;
            font-size: 1.5em;
            color: black;
        }
        .about-us, .services, .products, .contact-us, .note {
            padding: 20px;
            margin: 10px;
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        h2 {
            color: #333;
        }
        .image-placeholder {
            background-color: #ccc;
            padding: 20px;
            text-align: center;
            margin: 10px 0;
            color: #333;
        }
        .service-images, .product-images {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .service-images .image-placeholder, .product-images .image-placeholder {
            flex: 1 1 30%;
            margin: 5px;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin: 5px 0;
        }
        form input, form textarea {
            margin: 5px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            margin: 10px 0;
            padding: 10px;
            border: none;
            background-color: #3c3295;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #f1c40f;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #3c3295;
            color: white;
        }
        .note {
            background-color: #f1f1f1;
            padding: 20px;
            margin: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
       
    </style>
</head>
<body>
    <header>
        <div class="logo"><img src="https://media.istockphoto.com/id/1313644269/vector/gold-and-silver-circle-star-logo-template.jpg?s=612x612&w=0&k=20&c=hDqCI9qTkNqNcKa6XS7aBim7xKz8cZbnm80Z_xiU2DI="width="100" height="100"></div>
        <nav>
            <ul>
                <li><a href="service.jpg">Home</a></li>
                <li><a href="fkjsd.jpg">About Us</a></li>
                <li><a href="gjrfg.png">Services</a></li>
                <li><a href="jgirkg.png">Products</a></li>
                <li><a href="gjf.png">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
    <section>
        <div class="main"><img src="https://media.istockphoto.com/id/1313644269/vector/gold-and-silver-circle-star-logo-template.jpg?s=612x612&w=0&k=20&c=hDqCI9qTkNqNcKa6XS7aBim7xKz8cZbnm80Z_xiU2DI="width="300" height="300"></div>
           
     </section>    
       
        <section class="about-us">
            <h2>About Us</h2>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cum a suscipit consectetur, ipsum id totam? Non nihil modi maxime distinctio, repellat voluptas ratione impedit, libero! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cum a suscipit consectetur, ipsum id totam?</p>
            <div class="image-placeholder">
                <img src="https://media.istockphoto.com/id/1313644269/vector/gold-and-silver-circle-star-logo-template.jpg?s=612x612&w=0&k=20&c=hDqCI9qTkNqNcKa6XS7aBim7xKz8cZbnm80Z_xiU2DI=" alt="About Us Image"width="300" height="300">
            </div>
        </section>
        <section class="services">
            <h2>Services</h2>
            <div class="service-images">
                <div class="image-placeholder">
                    <img src="https://www.svgrepo.com/show/36558/sell-product.svg"alt="Service Image 01"width="300"height="200">
                </div>
                <div class="image-placeholder">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/1/14/Product_sample_icon_picture.png" alt="Service Image 02"width="300"height="200">
                </div>
                <div class="image-placeholder">
                    <img src="https://cdn2.vectorstock.com/i/1000x1000/85/36/services-and-products-icon-black-sign-vector-35248536.jpg="width="300"height="200">
                </div>
            </div>
            <a href="#">Click Here for more services</a>
        </section>
        <section class="products">
            <h2>Products</h2>
            <div class="product-images">
                <div class="image-placeholder">
                    <img src="https://cdn5.vectorstock.com/i/1000x1000/07/64/products-services-icon-black-sign-vector-35230764.jpg" alt="Product Image 01"width="300"height="200">
                </div>
                <div class="image-placeholder">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfepBYTbXhbXRW7yM8FIIGZFj8awC54pijrnVCfUKwUnE4-DbgfQfY5vDMAvOcjc5gM94&usqp=CAU" alt="Product Image 02">
                </div>
                <div class="image-placeholder">
                    <img src="https://cdn3.vectorstock.com/i/1000x1000/48/42/digital-product-icon-simple-element-vector-27064842.jpg" alt="Product Image 03"width="300"height="200">
                </div>
                <div class="image-placeholder">
                    <img src="https://cdn.vectorstock.com/i/1000v/79/10/product-icon-simple-element-vector-27077910.jpg" alt="Product Image 04"width="300"height="200">
                </div>
            </div>
            <a href="#">Click Here for more products</a>
        </section>
        <section class="contact-us">
            <h2 style=align-text:center>Contact Us</h2>
            <form>
                First Name :<input type="text" name="name">
                Last Name :<input type="text" name="name">
                City :<input type="text" name="name">
                Address:<input type="text" name="name">
                Requirements : <input type="textarea" name="name">
                <button type="submit">Submit</button>
                <button type="reset">Cancel</button>
            </form>
        </section>
    </main>
   
    </section>
</body>
</html>

