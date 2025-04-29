Yes, when you use Node.js with Puppeteer, it does consume memory and system resources because it 
launches a headless (or optionally full) Chromium browser, which is similar to launching a regular browser 
in the background. If you don’t close the browser after the task is complete, it will keep consuming 
memory and may lead to memory leaks or crashes over time.

How to properly close a Puppeteer session
