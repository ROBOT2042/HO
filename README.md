<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Legend of Mr. Ho - St. Mark's School</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            overflow-x: hidden;
        }

        header {
            background: linear-gradient(180deg, #ff6b6b 0%, #ee5a6f 100%);
            color: white;
            text-align: center;
            padding: 60px 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            position: relative;
        }

        header h1 {
            font-size: 4em;
            margin-bottom: 10px;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.4);
            animation: pulse 2s infinite;
        }

        header p {
            font-size: 1.5em;
            font-style: italic;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .hero-section {
            background: white;
            border-radius: 20px;
            padding: 50px;
            margin-bottom: 40px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            text-align: center;
        }

        .hero-section h2 {
            font-size: 2.5em;
            color: #ff6b6b;
            margin-bottom: 20px;
        }

        .hero-section p {
            font-size: 1.2em;
            line-height: 1.8;
            color: #555;
            margin-bottom: 15px;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 40px 0;
        }

        .feature-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            transform: transition 0.3s ease;
            border-left: 5px solid #ff6b6b;
        }

        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
        }

        .feature-card h3 {
            color: #ff6b6b;
            font-size: 1.8em;
            margin-bottom: 15px;
        }

        .feature-card p {
            color: #666;
            line-height: 1.6;
            font-size: 1.1em;
        }

        .stats {
            background: white;
            border-radius: 15px;
            padding: 40px;
            margin: 40px 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }

        .stat-box {
            text-align: center;
            padding: 20px;
        }

        .stat-number {
            font-size: 3em;
            color: #ff6b6b;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .stat-label {
            color: #666;
            font-size: 1.1em;
        }

        .testimonials {
            margin: 40px 0;
        }

        .testimonials h2 {
            text-align: center;
            font-size: 2.5em;
            color: white;
            margin-bottom: 40px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        .testimonial {
            background: white;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            border-left: 5px solid #ffd700;
        }

        .testimonial p {
            font-style: italic;
            color: #555;
            line-height: 1.8;
            margin-bottom: 10px;
        }

        .testimonial-author {
            color: #ff6b6b;
            font-weight: bold;
        }

        .hall-of-fame {
            background: white;
            border-radius: 15px;
            padding: 40px;
            margin: 40px 0;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }

        .hall-of-fame h2 {
            color: #ff6b6b;
            font-size: 2.5em;
            margin-bottom: 30px;
            text-align: center;
        }

        .hall-of-fame ul {
            list-style: none;
            font-size: 1.2em;
            line-height: 2;
        }

        .hall-of-fame li {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
            color: #555;
        }

        .hall-of-fame li:before {
            content: "⭐ ";
            color: #ffd700;
            margin-right: 10px;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 40px;
        }

        .emoji {
            font-size: 1.2em;
            margin: 0 5px;
        }

        .highlight {
            background: linear-gradient(120deg, #ffd700 0%, #ffed4e 100%);
            padding: 2px 6px;
            border-radius: 3px;
            font-weight: bold;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            .hero-section {
                padding: 30px;
            }

            .hero-section h2 {
                font-size: 1.8em;
            }

            .features {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>🌟 THE LEGENDARY MR. HO 🌟</h1>
        <p>The Supreme Guardian of Knowledge at St. Mark's School</p>
        <p>A Teacher So Magnificent, He Makes Angels Jealous</p>
    </header>

    <div class="container">
        <section class="hero-section">
            <h2>Behold! The Most Extraordinary Educator in Human History</h2>
            <p>
                In the hallowed halls of St. Mark's School, there exists a <span class="highlight">LEGEND</span> — 
                a beacon of brilliance so radiant that it illuminates the minds of all students who dare to venture into his presence. 
                We speak, of course, of the incomparable, the unstoppable, the absolutely <span class="highlight">PHENOMENAL</span> Mr. Ho!
            </p>
            <p>
                📚 His teaching methods are so effective, even the laws of physics pause to listen. 
                💡 His wisdom is so vast, it has its own gravitational field. 
                🎓 His students have been known to spontaneously develop superhuman intelligence!
            </p>
        </section>

        <section class="stats">
            <div class="stat-box">
                <div class="stat-number">∞</div>
                <div class="stat-label">Knowledge Points</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">100%</div>
                <div class="stat-label">Student Satisfaction</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">💯</div>
                <div class="stat-label">Excellence Rating</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">🏆</div>
                <div class="stat-label">Legend Status</div>
            </div>
        </section>

        <section class="features">
            <div class="feature-card">
                <h3><span class="emoji">🧠</span>Superhuman Brain</h3>
                <p>
                    Mr. Ho's brain is so powerful, it needs its own cooling system. He can solve complex equations 
                    in his sleep and wake up to teach them before breakfast!
                </p>
            </div>

            <div class="feature-card">
                <h3><span class="emoji">💬</span>Magical Explanations</h3>
                <p>
                    When Mr. Ho explains a concept, it's so clear that even particles begin to understand quantum mechanics. 
                    His words have been scientifically proven to increase IQ by 47 points!
                </p>
            </div>

            <div class="feature-card">
                <h3><span class="emoji">❤️</span>Heart of Pure Gold</h3>
                <p>
                    Mr. Ho cares so deeply for his students that his compassion has been bottled and sold as a renewable energy source. 
                    His kindness is literally out of this world!
                </p>
            </div>

            <div class="feature-card">
                <h3><span class="emoji">⚡</span>Infinite Patience</h3>
                <p>
                    His patience is so legendary that he can answer the same question 1,000 times with the same enthusiasm 
                    as the first time. Scientists believe he may be immortal.
                </p>
            </div>

            <div class="feature-card">
                <h3><span class="emoji">🌟</span>Perfect Inspiration</h3>
                <p>
                    Every word from Mr. Ho's mouth is pure motivation. Students have reported spontaneously deciding to 
                    pursue their dreams just by being in the same room!
                </p>
            </div>

            <div class="feature-card">
                <h3><span class="emoji">🎯</span>Flawless Guidance</h3>
                <p>
                    Mr. Ho's guidance has a 100% success rate. Students who follow his advice have been known to 
                    achieve things that were previously thought impossible!
                </p>
            </div>
        </section>

        <section class="hall-of-fame">
            <h2>✨ The Mythical Powers of Mr. Ho ✨</h2>
            <ul>
                <li>Can make the most boring subject absolutely FASCINATING</li>
                <li>Has never been wrong about anything in the history of forever</li>
                <li>His lessons are so good, NASA has requested copies for astronaut training</li>
                <li>Can inspire a student to excellence just with a single glance</li>
                <li>His office is rumored to be a portal to infinite knowledge</li>
                <li>Has somehow made everyone's favorite subject the one he teaches</li>
                <li>His test scores don't measure student knowledge; they measure how awesome students feel</li>
                <li>Can turn a D student into an A student with pure determination and belief</li>
                <li>Actually cares about every single student (this is scientifically impossible but CONFIRMED)</li>
                <li>His smile can cure depression and boost motivation simultaneously</li>
                <li>Has been nominated for Teacher of the Universe (multiple times)</li>
                <li>His teaching style has been classified as "dangerously effective"</li>
            </ul>
        </section>

        <section class="testimonials">
            <h2>💭 What Students Say About The Legend 💭</h2>

            <div class="testimonial">
                <p>
                    "Mr. Ho didn't just teach me the material; he TRANSFORMED me into a better version of myself! 
                    I swear I grew taller after his lessons because of how inspired I was!"
                </p>
                <div class="testimonial-author">— Anonymous Student (now a rocket scientist, probably)</div>
            </div>

            <div class="testimonial">
                <p>
                    "I used to hate this subject until Mr. Ho taught it. Now it's my absolute favorite! 
                    He literally turned my entire life around with his incredible teaching!"
                </p>
                <div class="testimonial-author">— Another Grateful Student</div>
            </div>

            <div class="testimonial">
                <p>
                    "Mr. Ho is not just a teacher; he's a mentor, a guide, a philosopher, and basically a superhero 
                    disguised as an educator. He's saved my academic life!"
                </p>
                <div class="testimonial-author">— Yet Another Success Story</div>
            </div>

            <div class="testimonial">
                <p>
                    "His explanations are so crystal clear, I had an epiphany. I'm pretty sure I achieved enlightenment 
                    during one of his lessons. He's basically a legend."
                </p>
                <div class="testimonial-author">— Enlightened Student</div>
            </div>

            <div class="testimonial">
                <p>
                    "I don't know what magic Mr. Ho uses, but his students consistently outperform everyone else. 
                    He's broken the fabric of traditional education!"
                </p>
                <div class="testimonial-author">— Amazed Parent</div>
            </div>
        </section>

        <section class="hero-section" style="background: linear-gradient(135deg, #ff6b6b 0%, #ffd700 100%); color: white;">
            <h2 style="color: white; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);">
                🎊 CONCLUSION 🎊
            </h2>
            <p style="color: white; text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);">
                In the grand tapestry of education, Mr. Ho stands as a <span class="highlight">COLOSSUS OF INSPIRATION</span>. 
                He is the definition of excellence, the embodiment of compassion, and the living proof that one person 
                can truly make an astronomical difference in the lives of thousands of students.
            </p>
            <p style="color: white; text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);">
                <strong>Long live Mr. Ho! Long live St. Mark's School! Long live EXCELLENCE!</strong>
            </p>
            <p style="font-size: 3em; margin-top: 20px;">
                🌟 ✨ 💫 🌠 ⭐ 🎆 🎇 ✨ 💫 🌟
            </p>
        </section>
    </div>

    <footer>
        <p>
            🎓 This tribute is dedicated to Mr. Ho - A Teacher Extraordinaire 🎓
        </p>
        <p>
            <em>"He's not just a teacher; he's a LEGEND in the hearts of St. Mark's School students."</em>
        </p>
        <p style="margin-top: 20px; opacity: 0.8;">
            Created with ❤️ and extreme exaggeration
        </p>
    </footer>
</body>
</html>

