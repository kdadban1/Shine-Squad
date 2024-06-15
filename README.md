<!DOCTYPE html>
<html lang="en">

     <header>
        <div class="logo">
            <img src="placeholder-logo.png" alt="Shine Squad Detailers Logo">
        </div>
        <div class="header-content">
            <h1>Shine Squad Detailers</h1>
            <p>Contact: <a href="mailto:shinesquaddetailers@gmail.com">shinesquaddetailers@gmail.com</a> | Phone: <a href="tel:619-507-8011">619-507-8011</a></p>
        </div>
    </header>
  <body>
    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. Duis sagittis ipsum. Praesent mauris. Fusce nec tellus sed augue semper porta. Mauris massa. Vestibulum lacinia arcu eget nulla.</p>
        </section>
        <br>
        <section id="prices">
            <h2>Prices</h2>
            <table>
                <thead>
                    <tr>
                        <th>Service</th>
                        <th>Price ($)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Full Car Detailing</td>
                        <td>150</td>
                    </tr>
                    <tr>
                        <td>Interior Cleaning</td>
                        <td>100</td>
                    </tr>
                    <tr>
                        <td>Exterior Cleaning</td>
                        <td>75</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>
    <footer>
            <button class="email-button" onclick="location.href='mailto:shinesquaddetailers@gmail.com'">Email Us</button>
      <br>
      <br>
        <z>&copy; 2024 Shine Squad Detailers. All rights reserved.</z>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

p {
  
}

header {
    display: flex;
    align-items: center;
    background-color: #006db0;
    color: #fff;
    padding: 20px;
    justify-content: center;
    position: relative;
}

.logo img {
    width: 50px; /* Adjust as needed */
    height: auto;
    position: absolute;
    left: 20px;
}

.header-content {
    text-align: center;
}

header h1 {
    margin: 0;
  font-size: 60px;
}

header p {
    margin: 5px 0 0;
  font-size: 30px;
}

header a {
    color: #ffd700;
    text-decoration: none;
}

.email-button {
    background-color: #ffd700;
    color: #333;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 16px;
    border-radius: 5px;
    margin-top: 10px;
    text-transform: uppercase;
}

.email-button:hover {
    background-color: #e6b800;
}

main {
    padding: 20px;
    max-width: 800px;
    margin: 0 auto;
}

main h2 {
    color: #333;
    text-align: center;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
}

table, th, td {
    border: 1px solid #ddd;
}

th, td {
    padding: 8px;
    text-align: left;
}

th {
            background-color: #006db0; 
            color: #fff;
        }

footer {
    background-color: #006db0;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

</style>
