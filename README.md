<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>How to Host on GitHub - Simple Guide</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: #333;
            line-height: 1.6;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .container {
            background: white;
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            margin-top: 20px;
        }
        
        header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 3px solid #6e5494;
            margin-bottom: 30px;
        }
        
        h1 {
            color: #6e5494;
            font-size: 2.2rem;
            margin-bottom: 10px;
        }
        
        h2 {
            color: #4078c0;
            margin: 25px 0 15px;
            padding-bottom: 8px;
            border-bottom: 2px dashed #eee;
        }
        
        h3 {
            color: #333;
            margin: 20px 0 10px;
        }
        
        .highlight-box {
            background: #f8f9ff;
            border-left: 5px solid #6e5494;
            padding: 20px;
            margin: 20px 0;
            border-radius: 0 10px 10px 0;
        }
        
        .step-box {
            background: #f0f8ff;
            border: 2px solid #c3dafe;
            border-radius: 15px;
            padding: 20px;
            margin: 25px 0;
            position: relative;
        }
        
        .step-number {
            display: inline-block;
            background: #6e5494;
            color: white;
            width: 36px;
            height: 36px;
            border-radius: 50%;
            text-align: center;
            line-height: 36px;
            font-weight: bold;
            position: absolute;
            top: -18px;
            left: 20px;
        }
        
        ul, ol {
            padding-left: 25px;
            margin: 15px 0;
        }
        
        li {
            margin-bottom: 10px;
        }
        
        code {
            background: #f1f1f1;
            padding: 3px 6px;
            border-radius: 4px;
            font-family: monospace;
            font-size: 0.9rem;
        }
        
        .link-box {
            text-align: center;
            background: linear-gradient(135deg, #6e5494, #4078c0);
            color: white;
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
        }
        
        .link-box a {
            color: white;
            font-weight: bold;
            font-size: 1.2rem;
            text-decoration: none;
            background: rgba(255,255,255,0.2);
            padding: 10px 20px;
            border-radius: 50px;
            display: inline-block;
            margin-top: 10px;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #ddd;
            color: #666;
            font-size: 0.9rem;
        }
        
        .emoji {
            font-size: 1.5rem;
        }
        
        @media (max-width: 600px) {
            body {
                padding: 10px;
            }
            
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🌐 Host Your First Webpage!</h1>
            <p><em>A simple guide to hosting websites on GitHub (no laptop needed!)</em></p>
        </header>
        
        <section class="highlight-box">
            <h2>📌 What's This About?</h2>
            <p><strong>Imagine:</strong><br>
            You just painted a cool poster. You want friends to see it, but you can't text it to everyone.<br>
            What if you could <strong>pin it on a public bulletin board</strong> that anyone can visit anytime?</p>
            
            <p><strong>That's GitHub for webpages!</strong><br>
            It's a free online bulletin board where you can "pin" your website so the whole world can see.</p>
        </section>
        
        <section>
            <h2>🔍 Let's Break It Down</h2>
            <p><strong>GitHub</strong> = A locker room where you store your project files online.<br>
            <strong>Hosting</strong> = Putting your website files in a special locker that also <strong>displays them like a museum</strong>.</p>
            
            <p>Think of it like <strong>TikTok but for code</strong>:</p>
            <ul>
                <li>You upload your creation (video/website).</li>
                <li>People get a link to view it.</li>
                <li>You can update it anytime.</li>
            </ul>
        </section>
        
        <section class="highlight-box">
            <h2>📱 Real-Life Example</h2>
            <ol>
                <li>You write a birthday invite in <strong>Canva</strong> (that's like making a webpage).</li>
                <li>You download it as a PDF (that's your <strong>HTML file</strong>).</li>
                <li>You upload it to Google Drive & share the link (that's <strong>GitHub hosting</strong>).</li>
            </ol>
        </section>
        
        <h2>🚀 Your 3-Step Plan</h2>
        <p><em>(Follow these steps exactly — no rabbit holes!)</em></p>
        
        <div class="step-box">
            <div class="step-number">1</div>
            <h3>Step 1: Make a GitHub Account (5 minutes)</h3>
            <ul>
                <li>Go to <strong>github.com</strong> in your browser</li>
                <li>Sign up (use your school email if possible)</li>
                <li>Username = Your internet nickname for projects</li>
            </ul>
            <p><em>Tip: Write down your username and password somewhere safe!</em></p>
        </div>
        
        <div class="step-box">
            <div class="step-number">2</div>
            <h3>Step 2: Create Your "Locker" (Repository)</h3>
            <ol>
                <li>Click the <strong>+</strong> icon (top right) → "New repository"</li>
                <li>Name it: <code>username.github.io</code><br>
                    <em>(Replace "username" with YOUR GitHub username — this is magical, it auto-hosts!)</em></li>
                <li>Check <strong>"Add a README file"</strong></li>
                <li>Click <strong>Create Repository</strong></li>
            </ol>
            <p><strong>Visual:</strong> It's like naming a folder "MY-WEBSITE" and GitHub gives it superpowers.</p>
        </div>
        
        <div class="step-box">
            <div class="step-number">3</div>
            <h3>Step 3: Upload Your Webpage Files</h3>
            <p><strong>Option A (Easiest — for total beginners on mobile):</strong></p>
            <ol>
                <li>Save this HTML code as a file:
                    <ul>
                        <li>Copy all this code (the entire page you're reading)</li>
                        <li>Open a text editor app (Google Docs, Notes, etc.)</li>
                        <li>Paste the code and save as <code>index.html</code></li>
                    </ul>
                </li>
                <li>In your GitHub repository, click <strong>"Add file" → "Upload files"</strong></li>
                <li>Select your HTML file from your phone</li>
                <li>Click <strong>Commit changes</strong> (means "save") at the bottom</li>
            </ol>
            <p><strong>Option B (Even easier if you're reading this on GitHub already):</strong><br>
            Just copy-paste this code directly into GitHub's editor!</p>
        </div>
        
        <div class="link-box">
            <h3 class="emoji">🎉 Done! Your Site is Now Live At:</h3>
            <p><strong>https://YOUR-USERNAME.github.io</strong></p>
            <p><em>(Replace "YOUR-USERNAME" with your actual GitHub username)</em></p>
            <a href="#" id="liveLink">Check My Live Site</a>
        </div>
        
        <section class="highlight-box">
            <h2>💡 Pro Tips for Mobile Users</h2>
            <ul>
                <li>GitHub works great on mobile browsers!</li>
                <li>Use landscape mode for easier navigation</li>
                <li>Bookmark your GitHub repository page</li>
                <li>You can edit files directly on GitHub if needed</li>
                <li>To update your site, just upload a new HTML file with the same name</li>
            </ul>
        </section>
        
        <footer>
            <p>Made with ❤️ for students hosting their first webpage</p>
            <p>You can send your link to your professor, friends, or put it in your Instagram bio!</p>
            <p><strong>Remember:</strong> No laptop required. Just your phone and 15 minutes!</p>
        </footer>
    </div>
    
    <script>
        // Simple script to make the link work
        document.getElementById('liveLink').addEventListener('click', function(e) {
            e.preventDefault();
            const username = prompt("Enter your GitHub username to visit your site:");
            if (username) {
                window.open(`https://${username}.github.io`, '_blank');
            }
        });
        
        // Add visual feedback for steps
        document.querySelectorAll('.step-box').forEach(box => {
            box.addEventListener('touchstart', function() {
                this.style.transform = 'scale(0.99)';
            });
            box.addEventListener('touchend', function() {
                this.style.transform = 'scale(1)';
            });
        });
    </script>
</body>
</html>
