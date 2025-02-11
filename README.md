<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Developer Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">
    <nav class="bg-blue-600 p-4 text-white flex justify-between items-center">
        <h1 class="text-2xl font-bold">My Portfolio</h1>
        <ul class="flex space-x-4">
            <li><a href="#about" class="hover:underline">About</a></li>
            <li><a href="#projects" class="hover:underline">Projects</a></li>
            <li><a href="#contact" class="hover:underline">Contact</a></li>
        </ul>
    </nav>
    
    <header class="text-center py-16 bg-blue-500 text-white">
        <h2 class="text-4xl font-bold">Hello, I'm a Dhruv raval</h2>
        <p class="text-lg mt-4">I build modern and responsive websites.</p>
    </header>
    
    <section id="about" class="max-w-4xl mx-auto p-6 text-center">
        <h2 class="text-3xl font-semibold">About Me</h2>
        <p class="mt-4">I'm a passionate web developer specializing in front-end and back-end technologies.</p>
    </section>
    
    <section id="projects" class="max-w-4xl mx-auto p-6">
        <h2 class="text-3xl font-semibold text-center">Projects</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-6">
            <div class="bg-white p-4 shadow-md rounded-lg">
                <h3 class="text-xl font-bold">Project 1</h3>
                <p class="mt-2">A responsive web app built with HTML, CSS, and JavaScript.</p>
            </div>
            <div class="bg-white p-4 shadow-md rounded-lg">
                <h3 class="text-xl font-bold">Project 2</h3>
                <p class="mt-2">A full-stack application using React and Node.js.</p>
            </div>
        </div>
    </section>
    
    <section id="contact" class="max-w-4xl mx-auto p-6 text-center">
        <h2 class="text-3xl font-semibold">Contact</h2>
        <p class="mt-4">Let's connect! Reach me at <a href="2201031000110@silveroakuni.ac.in" class="text-blue-500 font-bold">2201031000110@silveroakuni.ac.in</a></p>
    </section>
    
    <footer class="text-center p-4 bg-blue-600 text-white mt-6">
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
