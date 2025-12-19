# Ex.07 Restaurant Website
## Date:19/12/2025
REGT NO :25018945

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
~~~
<html>

<head>
    <title>
        Restaurant Website
    </title>
    <script src="https://cdn.tailwindcss.com">
    </script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet" />
    <link rel="stylesheet" href="res.css"/>

</head>

<body class="bg-gray-100">
    <!-- Navbar -->
    <nav class="bg-white shadow-lg">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between">
                <div class="flex space-x-7">
                    <div>
                        <a class="flex items-center py-4 px-2" href="#">
                            <img alt="Restaurant logo" class="h-8 w-8 mr-2" src="https://storage.googleapis.com/a1aa/image/eqGJFmD3iB37MSbhW1k6hHAxBFLDznVtO24ovoetosPYMVtTA.jpg" />
                            <span class="font-semibold text-gray-500 text-lg">
                                Master's Chef
                            </span>
                        </a>
                    </div>
                    <div class="hidden md:flex items-center space-x-1">
                        <a class="py-4 px-2 text-green-500 border-b-4 border-green-500 font-semibold" href="#">Home</a>
                        <a class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300" href="#menu">Menu</a>
                        <a class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300" href="#about">About</a>
                        <a class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300" href="#contact">Contact</a>
                        <a class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300" href="#admin">Admin</a>
                    </div>
                </div>
                <div class="md:hidden flex items-center">
                    <button class="outline-none mobile-menu-button">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>
    <!-- Mobile Menu -->
    <div class="hidden mobile-menu">
        <ul>
            <li><a class="block text-sm px-2 py-4 text-white bg-green-500 font-semibold" href="#">Home</a></li>
            <li><a class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300" href="#menu">Menu</a></li>
            <li><a class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300" href="#about">About</a></li>
            <li><a class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300" href="#contact">Contact</a></li>
            <li><a class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300" href="#admin">Admin</a></li>
        </ul>
    </div>
    <!-- Hero Section -->
    <div class="bg-cover bg-center h-screen" style="background-image: url('https://images.unsplash.com/photo-1514933651103-005eec06c04b?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');">
        <div class="flex items-center justify-center h-full bg-gray-900 bg-opacity-50">
            <div class="text-center">
                <h1 class="text-white text-5xl font-bold">
                    Welcome to Our Restaurant
                </h1>
                <p class="text-white text-xl mt-4">
                    Delicious food, cozy atmosphere
                </p>
                <a class="mt-6 inline-block bg-green-500 text-white py-2 px-4 rounded-full text-lg" href="#menu">
                    View Menu
                </a>
            </div>
        </div>
    </div>
    <!-- Menu Section -->
    <section class="py-20 bg-white" id="menu">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800">
                Our Menu
            </h2>
            <div class="mt-10 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://images.unsplash.com/photo-1464093515883-ec948246accb?q=80&w=2059&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width="300" />
                    <h3 class="text-xl font-semibold mt-4">
                        Lobster Ravioli and Scampi cream
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $12.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://images.unsplash.com/photo-1498531872221-ce6d6216be71?q=80&w=1931&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width="300" />
                    <h3 class="text-xl font-semibold mt-4">
                        Gourmet prawn
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $15.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://cdn.pixabay.com/photo/2015/05/02/01/02/chicken-bokeumtang-749365_960_720.jpg" width="300" />
                    <h3 class="text-xl font-semibold mt-4">
                        Dak Bokkeumtang
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $9.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://plus.unsplash.com/premium_photo-1668095398227-c943ddb69d89?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width="300" />
                    <h3 class="text-xl font-semibold mt-4">
                        Bruschetta with Smoked salmon
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $11.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://images.unsplash.com/photo-1516865131505-4dabf2efc692?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width="300" />
                    <h3 class="text-xl font-semibold mt-4">
                        Black Squid Ink Pasta
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $13.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://images.unsplash.com/photo-1583623025817-d180a2221d0a?q=80&w=2071&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width="300" />
                    <h3 class="text-xl font-semibold mt-4">

                        Sushi plate with chopsticks and soya souce.
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $14.99
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!-- About Section -->
    <section class="py-20 bg-gray-100" id="about">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800">
                About Us
            </h2>
            <div class="mt-10 flex flex-col md:flex-row items-center">
                <div class="md:w-1/2">
                    <img alt="Image of the restaurant interior" class="w-full h-auto rounded-lg shadow-lg" height="300" src="https://storage.googleapis.com/a1aa/image/N1sTxIDwMrKlChCUFTMlUUY336xae9RBRyF0Bikym2aNmq2JA.jpg" width="500" />
                </div>
                <div class="md:w-1/2 md:ml-10 mt-6 md:mt-0">
                    <p class="text-gray-600 text-lg">
                        Our restaurant has been serving delicious food to the community for over 20 years. We pride ourselves on using the freshest ingredients and providing a cozy atmosphere for our guests. Whether you're here for a quick bite or a special occasion, we strive to make every visit memorable.
                    </p>
                    <p class="text-gray-600 text-lg mt-4">
                        Our menu features a variety of dishes, from classic favorites to innovative new creations. We also offer a selection of fine wines and craft beers to complement your meal. Come and experience the best dining experience in town!
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section class="py-20 bg-white" id="contact">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800">
                Contact Us
            </h2>
            <div class="mt-10 flex flex-col md:flex-row items-center">
                <div class="md:w-1/2">
                    <form action="#" class="bg-gray-100 p-6 rounded-lg shadow-lg" method="POST">
                        <div class="mb-4">
                            <label class="block text-gray-700 font-bold mb-2" for="name">
                                Name
                            </label>
                            <input class="w-full px-3 py-2 border border-gray-300 rounded-lg" id="name" name="name" required="" type="text" />
                        </div>
                        <div class="mb-4">
                            <label class="block text-gray-700 font-bold mb-2" for="email">
                                Email
                            </label>
                            <input class="w-full px-3 py-2 border border-gray-300 rounded-lg" id="email" name="email" required="" type="email" />
                        </div>
                        <div class="mb-4">
                            <label class="block text-gray-700 font-bold mb-2" for="message">
                                Message
                            </label>
                            <textarea class="w-full px-3 py-2 border border-gray-300 rounded-lg" id="message" name="message" required="" rows="4"></textarea>
                        </div>
                        <button class="bg-green-500 text-white py-2 px-4 rounded-full" type="submit">
                            Send Message
                        </button>
                    </form>
                </div>
                <div class="md:w-1/2 md:ml-10 mt-6 md:mt-0">
                    <h3 class="text-2xl font-semibold text-gray-800">
                        Get in Touch
                    </h3>
                    <p class="text-gray-600 text-lg mt-4">
                        We'd love to hear from you! Whether you have a question about our menu, want to make a reservation, or just want to say hello, feel free to reach out to us.
                    </p>
                    <p class="text-gray-600 text-lg mt-4">
                        <i class="fas fa-phone-alt">
                        </i>
                        044 27162510
                    </p>
                    <p class="text-gray-600 text-lg mt-4">
                        <i class="fas fa-envelope">
                        </i>
                        info@24005998.com
                    </p>
                    <p class="text-gray-600 text-lg mt-4">
                        <i class="fas fa-map-marker-alt">
                        </i>
                        123 Main Street, Thiruverkadu, Chennai.
                    </p>
                </div>
            </div>
        </div>
    </section>
    <section class="py-20 bg-gray-100" id="admin">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800">Meet Our Team</h2>
            <div class="mt-10 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                <!-- Owner -->
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <img alt="Owner's Image" class="w-full h-40 object-cover rounded-t-lg" src="https://demo.solwininfotech.com/wordpress/justica/wp-content/uploads/2016/07/Attorneys-5.png" />
                    <h3 class="text-xl font-semibold mt-4">John Doe</h3>
                    <p class="text-gray-600 mt-2">Owner</p>
                </div>
                <!-- Partner -->
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <img alt="Partner's Image" class="w-full h-40 object-cover rounded-t-lg" src="https://static.wikia.nocookie.net/my-characters/images/f/f6/Jane_Smith.jpg/revision/latest?cb=20230316015917&path-prefix=pt-br" />
                    <h3 class="text-xl font-semibold mt-4">Jane Smith</h3>
                    <p class="text-gray-600 mt-2">Co-Owner & Partner</p>
                </div>
                <!-- Chef -->
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <img alt="Chef's Image" class="w-full h-40 object-cover rounded-t-lg" src="https://alexguarnaschelli.com/wp-content/uploads/2021/09/bio-image-2@2x-1024x636.jpg" />
                    <h3 class="text-xl font-semibold mt-4">Chef Alex</h3>
                    <p class="text-gray-600 mt-2">Head Chef</p>
                </div>
                <!-- Additional Team Members -->
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <img alt="Team Member Image" class="w-full h-40 object-cover rounded-t-lg" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrKyLgtoHthJIiZNEPhj7CApWCLzm0XPzrgw&s" />
                    <h3 class="text-xl font-semibold mt-4">Michael Lee</h3>
                    <p class="text-gray-600 mt-2">Sous Chef</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <img alt="Team Member Image" class="w-full h-40 object-cover rounded-t-lg" src="https://as.nyu.edu/content/dam/nyu-as/faculty/images/profilePhotos/a-f/davis-emily-cropped.png" />
                    <h3 class="text-xl font-semibold mt-4">Emily Davis</h3>
                    <p class="text-gray-600 mt-2">Pastry Chef</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer class="bg-gray-800 py-6">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between items-center">
                <p class="text-white">
                    © 2024 Restaurant Name. All rights reserved.
                </p>
                <div class="flex space-x-4">
                    <a class="text-white" href="#">
                        <i class="fab fa-facebook-f">
                        </i>
                    </a>
                    <a class="text-white" href="#">
                        <i class="fab fa-twitter">
                        </i>
                    </a>
                    <a class="text-white" href="#">
                        <i class="fab fa-instagram">
                        </i>
                    </a>
                </div>
            </div>
        </div>
    </footer>
    <script>
        const btn = document.querySelector("button.mobile-menu-button");
        const menu = document.querySelector(".mobile-menu");

        btn.addEventListener("click", () => {
            menu.classList.toggle("hidden");
        });
    </script>
</body>

</html>

~~~


## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-12-19 160622" src="https://github.com/user-attachments/assets/df9acc79-1c1e-4538-89af-7f4bcb9799ba" />
<img width="1920" height="1080" alt="Screenshot 2025-12-19 160639" src="https://github.com/user-attachments/assets/fac000ab-a3d4-4810-89e8-e77e57cabb17" />
<img width="1920" height="1080" alt="Screenshot 2025-12-19 160653" src="https://github.com/user-attachments/assets/4c58eb27-a9b8-4177-a7a3-be1426c1bd28" />
<img width="1649" height="568" alt="Screenshot 2025-12-19 161712" src="https://github.com/user-attachments/assets/5ab4db6a-e05b-43e5-b7f7-5a912cc343d2" />
<img width="1920" height="1080" alt="Screenshot 2025-12-19 194529" src="https://github.com/user-attachments/assets/4b320b4f-5354-4c6b-b24e-f39ebb72ecdc" />





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
