<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Urja Gold | Premium Ayurvedic Vitality</title>
    <style>
        :root {
            --deep-blue: #0A192F;
            --gold: #D4AF37;
            --light-gold: #F1D382;
            --white: #ffffff;
            --success: #27ae60;
            --star-color: #f1c40f;
        }

        body { font-family: 'Arial', sans-serif; margin: 0; padding: 0; background-color: var(--white); color: var(--deep-blue); scroll-behavior: smooth; }

        /* Header */
        header { background-color: var(--deep-blue); padding: 15px; text-align: center; border-bottom: 4px solid var(--gold); position: sticky; top: 0; z-index: 1000; }
        .logo { font-size: 24px; font-weight: bold; color: var(--gold); letter-spacing: 3px; }

        /* Hero */
        .hero {
            background: linear-gradient(rgba(10, 25, 47, 0.9), rgba(10, 25, 47, 0.9)), url('https://images.unsplash.com/photo-1512069772995-ec65ed45afd6?auto=format&fit=crop&q=80&w=1200');
            background-size: cover; color: white; padding: 60px 20px; text-align: center;
        }

        .btn-order {
            background-color: var(--gold); color: var(--deep-blue); padding: 18px 40px; text-decoration: none;
            font-weight: bold; font-size: 1.3rem; border-radius: 8px; display: inline-block; transition: 0.3s;
            border: none; cursor: pointer; text-transform: uppercase; box-shadow: 0 4px 15px rgba(212, 175, 55, 0.4);
        }

        /* Product Card */
        #order-section { padding: 40px 20px; text-align: center; background-color: #f4f4f4; }
        .product-card { background: white; max-width: 500px; margin: 0 auto; padding: 30px; border: 2px solid var(--gold); border-radius: 15px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }
        .product-image { width: 100%; max-width: 280px; height: auto; margin-bottom: 20px; }
        .trust-badge-image { width: 100%; max-width: 350px; height: auto; margin: 15px 0; }
        .price { font-size: 2.8rem; color: var(--success); margin: 10px 0; font-weight: bold; }
        .old-price { text-decoration: line-through; color: #888; font-size: 1.4rem; }

        /* Review Section */
        .reviews-container { max-width: 800px; margin: 50px auto; padding: 20px; text-align: center; }
        .review-card { background: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.05); margin-bottom: 20px; text-align: left; border-left: 5px solid var(--gold); }
        .review-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 10px; }
        .stars { color: var(--star-color); font-size: 1.2rem; }
        .reviewer-name { font-weight: bold; color: var(--deep-blue); }
        .review-text { font-style: italic; color: #555; }
        
        .btn-review { background: transparent; border: 2px solid var(--gold); color: var(--gold); padding: 10px 20px; border-radius: 5px; font-weight: bold; cursor: pointer; margin-top: 20px; transition: 0.3s; }
        .btn-review:hover { background: var(--gold); color: var(--deep-blue); }

        /* WhatsApp Float */
        .whatsapp-float { position: fixed; width: 60px; height: 60px; bottom: 20px; right: 20px; background-color: #25d366; color: #FFF; border-radius: 50px; text-align: center; font-size: 30px; box-shadow: 2px 2px 10px rgba(0,0,0,0.2); z-index: 10000; display: flex; align-items: center; justify-content: center; text-decoration: none; }

        footer { background: #050c18; color: #888; padding: 30px 20px; text-align: center; font-size: 0.8rem; }
    </style>
</head>
<body>

<a href="https://wa.me/918708029668?text=Hello,%20I%20have%20a%20question%20about%20Urja%20Gold" class="whatsapp-float" target="_blank">💬</a>

<header>
    <div class="logo">URJA GOLD</div>
</header>

<section class="hero">
    <h1>Power. Stamina. Results.</h1>
    <p>Join hundreds of satisfied men who reclaimed their vitality.</p>
    <a href="#order-section" class="btn-order">GET YOUR BOX NOW</a>
</section>

<section id="order-section">
    <div class="product-card">
        <img src="product-box.png" alt="Urja Gold Outer Box" class="product-image">
        <h2 style="margin: 0;">Urja Gold Vitality Course</h2>
        <img src="trust-badge.png" alt="Trust Badges" class="trust-badge-image">
        <div class="price">₹999 <span class="old-price">₹1,499</span></div>
        <button class="btn-order" onclick="window.location.href='checkout.html'">BUY NOW</button>
    </div>
</section>

<section class="reviews-container">
    <h2 style="font-size: 2rem; color: var(--deep-blue);">What Our Customers Say</h2>
    <p>Real stories from verified buyers.</p>

    <div class="review-card">
        <div class="review-header">
            <span class="reviewer-name">Rahul K. (Jaipur)</span>
            <span class="stars">★★★★★</span>
        </div>
        <p class="review-text">"Really impressed with the results. It took about 10 days to start feeling the energy, but it's worth it. Packing was totally plain, very discreet."</p>
    </div>

    <div class="review-card">
        <div class="review-header">
            <span class="reviewer-name">Amit S. (Delhi)</span>
            <span class="stars">★★★★★</span>
        </div>
        <p class="review-text">"Using it for 3 weeks now. My stamina and confidence have definitely improved. Delivery was fast too."</p>
    </div>

    <div class="review-card">
        <div class="review-header">
            <span class="reviewer-name">Vikram P. (Mumbai)</span>
            <span class="stars">★★★★☆</span>
        </div>
        <p class="review-text">"Good quality Ayurvedic product. No side effects. I recommend it to anyone looking for natural wellness."</p>
    </div>

    <button class="btn-review" onclick="window.location.href='https://wa.me/918708029668?text=I%20want%20to%20submit%20a%20review%20for%20Urja%20Gold'">Submit Your Review</button>
</section>

<footer>
    <p><strong>URJA GOLD WELLNESS INDIA</strong></p>
    <p>Customer Support: +91 8708029668</p>
    <p>AYUSH LIC NO: 123456789 | GMP Quality</p>
    
    <a href="admin.html" class="admin-link">Staff Login</a>
</footer>

</body>
</html>
