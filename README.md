<!DOCTYPE html>
<html>
<head>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="p-8 bg-gray-900 text-white max-w-xl mx-auto font-mono">

  <!-- Terminal-style git walkthrough -->
  <div class="bg-gray-800 rounded-2xl overflow-hidden shadow-2xl">

    <!-- Terminal title bar -->
    <div class="flex items-center gap-2 px-4 py-3 bg-gray-700 border-b border-gray-600">
      <div class="w-3 h-3 rounded-full bg-red-500"></div>
      <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
      <div class="w-3 h-3 rounded-full bg-green-500"></div>
      <span class="ml-2 text-xs text-gray-400">Terminal — my-first-site</span>
    </div>

    <!-- Terminal content -->
    <div class="p-5 text-sm space-y-3">

      <div>
        <p class="text-gray-500"># Clone the repo from GitHub</p>
        <p class="text-green-400">$ git clone https://github.com/you/my-first-site.git</p>
        <p class="text-gray-400 text-xs mt-1">Cloning into 'my-first-site'... done.</p>
      </div>

      <div>
        <p class="text-gray-500"># Check what's changed</p>
        <p class="text-green-400">$ git status</p>
        <p class="text-gray-400 text-xs mt-1">modified: index.html</p>
      </div>

      <div>
        <p class="text-gray-500"># Stage all changes</p>
        <p class="text-green-400">$ git add .</p>
      </div>

      <div>
        <p class="text-gray-500"># Commit with a message</p>
        <p class="text-green-400">$ git commit -m "Add homepage with intro section"</p>
        <p class="text-gray-400 text-xs mt-1">[main 3a7f2c1] Add homepage with intro section</p>
      </div>

      <div>
        <p class="text-gray-500"># Push to GitHub</p>
        <p class="text-green-400">$ git push</p>
        <p class="text-gray-400 text-xs mt-1">To github.com:you/my-first-site.git</p>
        <p class="text-gray-400 text-xs">   main -> main ✓</p>
      </div>

    </div>
  </div>

</body>
</html>
# my-first-site
