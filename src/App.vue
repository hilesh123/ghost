<template>
  <div class="main-header">
    <!-- Add the Spline viewer here -->
    <div class="spline-container">
      <spline-viewer class="spline" url="https://prod.spline.design/DPXMFQSStVTczeJ6/scene.splinecode"></spline-viewer>
    </div>
    
    <div class="gradient-overlay"></div>
    <div class="main-body"></div>
    
    <div class="nav-bar">
      <header>
        <h1>.CODE</h1>
      </header>
      <input type="checkbox" id="menu-toggle" class="menu-toggle">
      <label for="menu-toggle" class="menu-icon">&#9776;</label>
      <nav>
        <a href="#Home">Home</a>
        <a href="#About">About</a>
        <a href="#technologies">Languages</a>
        <a href="#frameworks">Frameworks</a>
      </nav>
    </div>
    
    <section id="Home">
      <div>
        <div class="intro">Introduction</div>
      </div>
      <div class="part1">
        <h1>WORLD FOR<br>DEVELOPERS</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur deleniti ducimus, repellendus laboriosam suscipit veniam accusamus cumque optio laudantium officia incidunt maiores odio voluptatum, maxime similique magnam aperiam voluptatibus cupiditate!</p>
      </div>
      <div class="last1">
        <button>Documentation</button>
        <button>Get Started</button>
      </div>
    </section>

    <section id="About" class="about-section">
      <div class="about-header">
        <div class="about-title">About .CODE</div>
      </div>
      <div class="about-content">
        <div class="about-mission">
          <h2>Our Mission</h2>
          <p>We are dedicated to empowering developers through comprehensive resources, cutting-edge tools, and a supportive community. Our platform is designed to make coding accessible, efficient, and enjoyable for everyone from beginners to experts.</p>
        </div>
        
        <div class="about-cards-container">
          <div class="about-card">
            <div class="card-icon">
              <i class="code-icon">{ }</i>
            </div>
            <h3>Learn</h3>
            <p>Access structured learning paths for multiple programming languages and frameworks tailored to all skill levels.</p>
          </div>
          
          <div class="about-card">
            <div class="card-icon">
              <i class="build-icon">&lt;/&gt;</i>
            </div>
            <h3>Build</h3>
            <p>Create amazing projects with our interactive development environments and extensive code libraries.</p>
          </div>
          
          <div class="about-card">
            <div class="card-icon">
              <i class="connect-icon">&#9741;</i>
            </div>
            <h3>Connect</h3>
            <p>Join a global community of developers to collaborate, share insights, and grow your network.</p>
          </div>
        </div>
        
        <div class="tech-stack" id="technologies">
          <h2>Technologies We Cover</h2>
          <div class="tech-slider-container">
            <div class="tech-grid">
              <div class="tech-item">
                <div class="tech-logo js">JS</div>
                <span>JavaScript</span>
                <div class="tech-description">
                  <p>A versatile language for web development, powering interactive and dynamic content.</p>
                </div>
              </div>
              <div class="tech-item">
                <div class="tech-logo py">Py</div>
                <span>Python</span>
                <div class="tech-description">
                  <p>Popular for data science, AI, and backend development with clean, readable syntax.</p>
                </div>
              </div>
              <div class="tech-item">
                <div class="tech-logo java">Jv</div>
                <span>Java</span>
                <div class="tech-description">
                  <p>Enterprise-grade language known for reliability, performance, and platform independence.</p>
                </div>
              </div>
              <div class="tech-item">
                <div class="tech-logo csharp">C#</div>
                <span>C Sharp</span>
                <div class="tech-description">
                  <p>Microsoft's powerful language for Windows apps, game development, and enterprise solutions.</p>
                </div>
              </div>
              <div class="tech-item">
                <div class="tech-logo c">C</div>
                <span>C</span>
                <div class="tech-description">
                  <p>The foundation of modern programming, ideal for system programming and embedded systems.</p>
                </div>
              </div>
              <div class="tech-item">
                <div class="tech-logo rust">Rs</div>
                <span>Rust</span>
                <div class="tech-description">
                  <p>Modern language focused on safety, performance, and concurrency without sacrificing speed.</p>
                </div>
              </div>
              <div class="tech-item">
                <div class="tech-logo ruby">Rb</div>
                <span>Ruby</span>
                <div class="tech-description">
                  <p>Elegant language designed for programmer happiness and productivity.</p>
                </div>
              </div>
              <div class="tech-item">
                <div class="tech-logo php">PHP</div>
                <span>PHP</span>
                <div class="tech-description">
                  <p>Server-side scripting language powering millions of websites and web applications.</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="framework-stack" id="frameworks">
          <h2>Frameworks & Tools We Love</h2>
          <div class="framework-showcase">
            <div class="framework-grid">
              <div class="framework-item">
                <div class="framework-logo vue">Vue</div>
                <span>Vue.js</span>
                <div class="framework-details">
                  <p>Progressive JavaScript framework for building user interfaces with easy integration.</p>
                </div>
              </div>
              <div class="framework-item">
                <div class="framework-logo react">React</div>
                <span>React.js</span>
                <div class="framework-details">
                  <p>Facebook's library for building interactive UIs with a component-based approach.</p>
                </div>
              </div>
              <div class="framework-item">
                <div class="framework-logo express">Ex</div>
                <span>Express.js</span>
                <div class="framework-details">
                  <p>Fast, minimalist web framework for Node.js, perfect for APIs and web applications.</p>
                </div>
              </div>
              <div class="framework-item">
                <div class="framework-logo node">Node</div>
                <span>Node.js</span>
                <div class="framework-details">
                  <p>JavaScript runtime built on Chrome's V8 engine for server-side applications.</p>
                </div>
              </div>
              <div class="framework-item">
                <div class="framework-logo django">Dj</div>
                <span>Django</span>
                <div class="framework-details">
                  <p>High-level Python web framework encouraging rapid development and clean design.</p>
                </div>
              </div>
              <div class="framework-item">
                <div class="framework-logo html">HTML</div>
                <span>HTML5</span>
                <div class="framework-details">
                  <p>The latest evolution of the standard that defines the structure of web content.</p>
                </div>
              </div>
              <div class="framework-item">
                <div class="framework-logo css">CSS</div>
                <span>CSS3</span>
                <div class="framework-details">
                  <p>Styling language that brings design and layout to web pages with modern features.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <div class="join-community">
          <h2>Join Our Developer Community</h2>
          <p>Get involved and take your coding journey to the next level. Our community offers mentorship programs, code reviews, collaborative projects, and regular tech talks.</p>
          <button class="community-btn">Join Community</button>
        </div>
      </div>
    </section>
    
  </div>
</template>

<script>
export default {
  name: 'WorldCode',
  mounted() {
    // Dynamically import the Spline viewer script
    const script = document.createElement('script')
    script.type = 'module'
    script.src = 'https://unpkg.com/@splinetool/viewer@1.9.95/build/spline-viewer.js'
    document.head.appendChild(script)
    
    // Add event listeners for hover effects on tech and framework items
    const techItems = document.querySelectorAll('.tech-item');
    techItems.forEach(item => {
      item.addEventListener('mouseenter', function() {
        this.classList.add('active');
      });
      item.addEventListener('mouseleave', function() {
        this.classList.remove('active');
      });
    });
    
    const frameworkItems = document.querySelectorAll('.framework-item');
    frameworkItems.forEach(item => {
      item.addEventListener('mouseenter', function() {
        this.classList.add('active');
      });
      item.addEventListener('mouseleave', function() {
        this.classList.remove('active');
      });
    });
  }
}
</script>

<style>
/* Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  width: 100%;
  background-color: black;
  color: white;
  min-height: 100vh;
  line-height: 1.5;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  overflow-x: hidden;
}

/* Gradient and Visual Effects */
.gradient-overlay {
  position: absolute;
  top: 0;
  right: 0;
  width: 100%;
  height: 100vh;
  background: radial-gradient(circle at top right, rgba(111, 0, 255, 0.3) 0%, rgba(0, 0, 0, 0.8) 70%);
  z-index: -2;
  pointer-events: none;
}

.main-body {
  position: absolute;
  height: 0;
  width: 30rem;
  top: 20%;
  right: 0;
  box-shadow: 0 0 700px 15px rgba(255, 255, 255, 0.3);
  rotate: -30deg;
  z-index: -3;
}

/* Spline 3D Element */
.spline-container {
  position: absolute;
  top: 0;
  right: 0;
  pointer-events: none;
  width: 100%;
  height: 100vh;
  z-index: -1;
  overflow: hidden;
}

.spline {
  position: absolute;
  right: -20%;
  top: 0;
  width: 120%;
  height: 100vh;
  transform: scale(0.8);
}

/* Navigation Bar */
.nav-bar {
  display: flex;
  justify-content: space-between;
  width: 100%;
  align-items: center;
  padding: 1.5rem 5%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000;
  background: rgba(0, 0, 0, 0.7);
  backdrop-filter: blur(10px);
}

.nav-bar header h1 {
  font-size: 2rem;
  font-weight: bold;
  background: linear-gradient(45deg, #9d4edd, #5a189a);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  text-shadow: 0 0 10px rgba(157, 78, 221, 0.5);
}

.menu-toggle {
  display: none;
}

.menu-icon {
  display: none;
  font-size: 1.8rem;
  cursor: pointer;
  color: white;
}

nav {
  display: flex;
  align-items: center;
  gap: 2rem;
}

nav a {
  color: white;
  font-size: 1rem;
  letter-spacing: 0.1rem;
  text-decoration: none;
  position: relative;
  padding: 0.5rem 0;
}

nav a::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 2px;
  background: linear-gradient(45deg, #9d4edd, #5a189a);
  transition: width 0.3s ease;
}

nav a:hover::after {
  width: 100%;
}

/* Home Section */
#Home {
  padding-top: 10rem;
  margin-left: 5%;
  width: 50%;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.intro {
  position: relative;
  width: 15rem;
  height: 2.5rem;
  padding-top: 8px;
  border-radius: 1.5rem;
  text-align: center;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  letter-spacing: 1px;
  box-shadow: 0 0 15px rgba(255,255,255,0.3);
  background: rgba(30, 30, 30, 0.6);
  transition: all 0.6s ease;
}

.intro:hover {
  box-shadow: 0 0 20px rgba(176, 9, 253, 0.7);
  transform: translateY(-5px);
}

.part1 h1 {
  margin-top: 2rem;
  font-size: 3.5rem;
  margin-left: 6px;
  letter-spacing: 0.1rem;
  background: linear-gradient(45deg, #ffffff, #9d4edd);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  text-shadow: 0 0 5px rgba(255, 255, 255, 0.3);
  transition: all 0.6s ease;
}

.part1 h1:hover {
  text-shadow: 0 0 15px rgba(176, 9, 253, 0.7);
  transform: translateY(-5px);
}

.part1 p {
  margin-top: 1.5rem;
  margin-left: 6px;
  letter-spacing: 0.2px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: 1.1rem;
  max-width: 90%;
  transition: all 0.5s ease-in;
}

.part1 p:hover {
  color: #bd93f9;
}

.last1 {
  margin-top: 3rem;
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
}

.last1 button {
  min-width: 10rem;
  padding: 0.8rem 1.5rem;
  border-radius: 2rem;
  color: white;
  border: 1px solid #6a0dad;
  background: rgba(106, 13, 173, 0.2);
  letter-spacing: 1px;
  font-size: 1rem;
  cursor: pointer;
  transition: all 0.5s ease;
  backdrop-filter: blur(5px);
}

.last1 button:hover {
  color: black;
  background-color: white;
  font-weight: bold;
  box-shadow: 0 0 15px rgba(176, 9, 253, 0.7);
  transform: translateY(-5px);
}

/* About Section */
.about-section {
  padding: 5rem 0;
  width: 90%;
  max-width: 1400px;
  margin: 0 auto;
}

.about-header {
  margin-bottom: 3rem;
  display: flex;
  justify-content: center;
}

.about-title {
  position: relative;
  width: 18rem;
  height: 2.8rem;
  padding-top: 8px;
  border-radius: 1.5rem;
  text-align: center;
  font-size: 1.5rem;
  font-weight: bold;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  letter-spacing: 1px;
  box-shadow: 0 0 15px rgba(255,255,255,0.3);
  background: rgba(30, 30, 30, 0.6);
  transition: all 0.6s ease;
}

.about-title:hover {
  box-shadow: 0 0 20px rgba(176, 9, 253, 0.7);
  transform: translateY(-5px);
}

.about-content {
  display: flex;
  flex-direction: column;
  gap: 5rem;
}

.about-mission h2 {
  font-size: 2.2rem;
  margin-bottom: 1.5rem;
  letter-spacing: 0.1rem;
  color: #f0f0f0;
  position: relative;
  display: inline-block;
}

.about-mission h2::after {
  content: '';
  position: absolute;
  bottom: -10px;
  left: 0;
  width: 60px;
  height: 4px;
  background: linear-gradient(to right, #9d4edd, #5a189a);
  border-radius: 2px;
}

.about-mission p {
  font-size: 1.2rem;
  max-width: 90%;
  line-height: 1.8;
}

.about-cards-container {
  display: flex;
  justify-content: space-between;
  gap: 2rem;
  margin-top: 2rem;
}

.about-card {
  flex: 1;
  background: rgba(20, 20, 20, 0.8);
  border: 1px solid rgba(100, 100, 100, 0.3);
  border-radius: 15px;
  padding: 2rem;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  position: relative;
  overflow: hidden;
}

.about-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 5px;
  background: linear-gradient(90deg, #6a0dad, #bd93f9);
  transform: scaleX(0);
  transform-origin: left;
  transition: transform 0.5s ease;
}

.about-card:hover::before {
  transform: scaleX(1);
}

.about-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 30px rgba(176, 9, 253, 0.2);
}

.card-icon {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
  color: #bd93f9;
  text-align: center;
}

.about-card h3 {
  font-size: 1.8rem;
  margin-bottom: 1rem;
  color: #f0f0f0;
}

.about-card p {
  font-size: 1rem;
  color: #cccccc;
  line-height: 1.6;
}

/* Technologies Section */
.tech-stack {
  margin: 2rem 0 5rem;
  padding: 3rem 0;
  background: rgba(15, 15, 15, 0.6);
  border-radius: 20px;
  position: relative;
}

.tech-stack::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at center, transparent 0%, rgba(0, 0, 0, 0.8) 100%);
  border-radius: 20px;
  z-index: -1;
}

.tech-stack h2 {
  font-size: 2.2rem;
  margin-bottom: 3rem;
  letter-spacing: 0.1rem;
  color: #f0f0f0;
  text-align: center;
  position: relative;
  display: inline-block;
  left: 50%;
  transform: translateX(-50%);
}

.tech-stack h2::after {
  content: '';
  position: absolute;
  bottom: -10px;
  left: 25%;
  width: 50%;
  height: 4px;
  background: linear-gradient(to right, #9d4edd, #5a189a);
  border-radius: 2px;
}

.tech-slider-container {
  width: 100%;
  overflow: hidden;
  padding: 1.5rem 0;
}

.tech-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
  padding: 0 3rem;
}

.tech-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1.5rem;
  background: rgba(30, 30, 30, 0.7);
  border-radius: 15px;
  transition: all 0.4s ease;
  position: relative;
  overflow: hidden;
  height: 220px;
  cursor: pointer;
}

.tech-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.2);
  transform: scaleY(0);
  transform-origin: bottom;
  transition: transform 0.4s ease;
  z-index: 0;
}

.tech-item:hover::before,
.tech-item.active::before {
  transform: scaleY(1);
}

.tech-item:hover,
.tech-item.active {
  transform: translateY(-10px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

.tech-logo {
  width: 5rem;
  height: 5rem;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.8rem;
  font-weight: bold;
  margin-bottom: 1rem;
  z-index: 1;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
  transition: all 0.4s ease;
}

.tech-item:hover .tech-logo,
.tech-item.active .tech-logo {
  transform: scale(1.1);
}

.tech-item span {
  font-size: 1.1rem;
  font-weight: 600;
  margin: 0.8rem 0;
  color: #f0f0f0;
  z-index: 1;
  transition: all 0.4s ease;
}

.tech-description {
  opacity: 0;
  max-height: 0;
  overflow: hidden;
  transition: all 0.4s ease;
  text-align: center;
  z-index: 1;
}

.tech-item:hover .tech-description,
.tech-item.active .tech-description {
  opacity: 1;
  max-height: 100px;
}

.tech-description p {
  font-size: 0.9rem;
  color: #cccccc;
  padding: 0 0.5rem;
}

/* Technology Logo Colors */
.js {
  background: linear-gradient(135deg, #f7df1e 0%, #eac116 100%);
  color: #000;
}

.js:hover {
  box-shadow: 0 0 25px rgba(247, 223, 30, 0.5);
}

.py {
  background: linear-gradient(135deg, #3776ab 0%, #2a5880 100%);
  color: #ebebeb;
}

.py:hover {
  box-shadow: 0 0 25px rgba(55, 118, 171, 0.5);
}

.java {
  background: linear-gradient(135deg, #f89820 0%, #e76f00 100%);
  color: #fff;
}

.java:hover {
  box-shadow: 0 0 25px rgba(231, 111, 0, 0.5);
}

.csharp {
  background: linear-gradient(135deg, #6a1577 0%, #9b4993 100%);
  color: #fff;
}

.csharp:hover {
  box-shadow: 0 0 25px rgba(106, 21, 119, 0.5);
}

.c {
  background: linear-gradient(135deg, #00acd7 0%, #007d9c 100%);
  color: #fff;
}

.c:hover {
  box-shadow: 0 0 25px rgba(0, 172, 215, 0.5);
}

.rust {
  background: linear-gradient(135deg, #b7410e 0%, #8c3302 100%);
  color: #fff;
}

.rust:hover {
  box-shadow: 0 0 25px rgba(183, 65, 14, 0.5);
}

.ruby {
  background: linear-gradient(135deg, #cc342d 0%, #9e100e 100%);
  color: #fff;
}

.ruby:hover {
  box-shadow: 0 0 25px rgba(204, 52, 45, 0.5);
}

.php {
  background: linear-gradient(135deg, #777bb3 0%, #4f5b93 100%);
  color: #fff;
}

.php:hover {
  box-shadow: 0 0 25px rgba(79, 91, 147, 0.5);
}

/* Frameworks Section */
.framework-stack {
  margin: 5rem 0;
  padding: 3rem 0;
  background: rgba(15, 15, 15, 0.6);
  border-radius: 20px;
  position: relative;
}

.framework-stack::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at center, transparent 0%, rgba(0, 0, 0, 0.8) 100%);
  border-radius: 20px;
  z-index: -1;
}

.framework-stack h2 {
  font-size: 2.2rem;
  margin-bottom: 3rem;
  letter-spacing: 0.1rem;
  color: #f0f0f0;
  text-align: center;
  position: relative;
  display: inline-block;
  left: 50%;
  transform: translateX(-50%);
}

.framework-stack h2::after {
  content: '';
  position: absolute;
  bottom: -10px;
  left: 25%;
  width: 50%;
  height: 4px;
  background: linear-gradient(to right, #9d4edd, #5a189a);
  border-radius: 2px;
}

.framework-showcase {
  width: 100%;
  overflow: hidden;
  padding: 1.5rem 0;
}

.framework-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
  padding: 0 3rem;
}

.framework-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1.5rem;
  background: rgba(30, 30, 30, 0.7);
  border-radius: 15px;
  transition: all 0.4s ease;
  position: relative;
  overflow: hidden;
  height: 220px;
  cursor: pointer;
}

.framework-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.2);
  transform: scaleY(0);
  transform-origin: bottom;
  transition: transform 0.4s ease;
  z-index: 0;
}

.framework-item:hover::before,
.framework-item.active::before {
  transform: scaleY(1);
}

.framework-item:hover,
.framework-item.active {
  transform: translateY(-10px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

.framework-logo {
  width: 5rem;
  height: 5rem;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.3rem;
  font-weight: bold;
  margin-bottom: 1rem;
  z-index: 1;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
  transition: all 0.4s ease;
}

.framework-item:hover .framework-logo,
.framework-item.active .framework-logo {
  transform: scale(1.1);
}

.framework-item span {
  font-size: 1.1rem;
  font-weight: 600;
  margin: 0.8rem 0;
  color: #f0f0f0;
  z-index: 1;
  transition: all 0.4s ease;
}

.framework-details {
  opacity: 0;
  max-height: 0;
  overflow: hidden;
  transition: all 0.4s ease;
  text-align: center;
  z-index: 1;
}

.framework-item:hover .framework-details,
.framework-item.active .framework-details {
  opacity: 1;
  max-height: 100px;
}

.framework-details p {
  font-size: 0.9rem;
  color: #cccccc;
  padding: 0 0.5rem;
}

/* Framework Logo Colors */
.vue {
  background: linear-gradient(135deg, #42b883 0%, #35495e 100%);
  color: #fff;
}

.vue:hover {
  box-shadow: 0 0 25px rgba(66, 184, 131, 0.5);
}

.react {
  background: linear-gradient(135deg, #61dafb 0%, #20232a 100%);
  color: #000;
}

.react:hover {
  box-shadow: 0 0 25px rgba(97, 218, 251, 0.5);
}

.express {
  background: linear-gradient(135deg, #000000 0%, #333333 100%);
  color: #fff;
}

.express:hover {
  box-shadow: 0 0 25px rgba(255, 255, 255, 0.3);
}

.node {
  background: linear-gradient(135deg, #3c873a 0%, #245826 100%);
  color: #fff;
}

.node:hover {
  box-shadow: 0 0 25px rgba(60, 135, 58, 0.5);
}

.django {
  background: linear-gradient(135deg, #092e20 0%, #136149 100%);
  color: #fff;
}

.django:hover {
  box-shadow: 0 0 25px rgba(9, 46, 32, 0.5);
}

.html {
  background: linear-gradient(135deg, #e34c26 0%, #d84924 100%);
  color: #fff;
}

.html:hover {
  box-shadow: 0 0 25px rgba(227, 76, 38, 0.5);
}

.css {
  background: linear-gradient(135deg, #2965f1 0%, #264de4 100%);
  color: #fff;
}

.css:hover {
  box-shadow: 0 0 25px rgba(41, 101, 241, 0.5);
}

/* Community Section */
.join-community {
  text-align: center;
  padding: 3rem;
  background: rgba(20, 20, 20, 0.8);
  border-radius: 20px;
  border: 1px solid rgba(100, 100, 100, 0.2);
  margin-top: 3rem;
  position: relative;
  overflow: hidden;
}

.join-community::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at center, rgba(106, 13, 173, 0.1) 0%, rgba(0, 0, 0, 0) 70%);
  z-index: -1;
}

.join-community h2 {
  font-size: 2.2rem;
  margin-bottom: 1.5rem;
  color: #f0f0f0;
  position: relative;
  display: inline-block;
}

.join-community h2::after {
  content: '';
  position: absolute;
  bottom: -10px;
  left: 25%;
  width: 50%;
  height: 4px;
  background: linear-gradient(to right, #9d4edd, #5a189a);
  border-radius: 2px;
}

.join-community p {
  max-width: 80%;
  margin: 0 auto 2.5rem;
  font-size: 1.2rem;
  color: #cccccc;
  line-height: 1.7;
}

.community-btn {
  padding: 1rem 2.5rem;
  border-radius: 2rem;
  text-decoration: none;
  color: white;
  border: 1px solid #6a0dad;
  background: rgba(106, 13, 173, 0.2);
  letter-spacing: 1px;
  font-size: 1.1rem;
  cursor: pointer;
  transition: all 0.5s ease;
  backdrop-filter: blur(5px);
}

.community-btn:hover {
  color: black;
  background-color: white;
  font-weight: bold;
  box-shadow: 0 0 20px rgba(176, 9, 253, 0.7);
  transform: translateY(-5px);
}

/* Responsive Design */
@media screen and (max-width: 1200px) {
  .spline {
    right: -30%;
    transform: scale(0.7);
  }
  
  #Home {
    width: 60%;
  }
  
  .about-section {
    width: 95%;
  }
  
  .about-cards-container {
    flex-wrap: wrap;
  }
  
  .about-card {
    flex: 0 1 calc(50% - 1rem);
    margin-bottom: 2rem;
  }
  
  .tech-grid,
  .framework-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

@media screen and (max-width: 992px) {
  .nav-bar {
    padding: 1rem 5%;
  }
  
  .spline {
    display: none;
  }
  
  #Home {
    width: 80%;
    margin: 0 auto;
    padding-top: 8rem;
    text-align: center;
  }
  
  .intro {
    margin: 0 auto;
  }
  
  .part1 h1 {
    font-size: 3rem;
  }
  
  .part1 p {
    margin: 1.5rem auto;
    max-width: 100%;
  }
  
  .last1 {
    justify-content: center;
  }
  
  .about-card {
    flex: 0 1 100%;
  }
  
  .tech-grid,
  .framework-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 1.5rem;
  }
}

@media screen and (max-width: 768px) {
  .nav-bar {
    flex-wrap: wrap;
  }
  
  .menu-icon {
    display: block;
  }
  
  nav {
    flex-direction: column;
    align-items: flex-start;
    width: 100%;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.5s ease;
    gap: 0;
  }
  
  .menu-toggle:checked ~ nav {
    max-height: 300px;
  }
  
  nav a {
    display: block;
    width: 100%;
    padding: 1rem 0;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
  }
  
  nav a::after {
    display: none;
  }
  
  #Home {
    width: 90%;
    padding-top: 6rem;
  }
  
  .part1 h1 {
    font-size: 2.5rem;
  }
  
  .about-mission h2,
  .tech-stack h2,
  .framework-stack h2,
  .join-community h2 {
    font-size: 1.8rem;
  }
  
  .tech-grid,
  .framework-grid {
    grid-template-columns: repeat(1, 1fr);
    padding: 0 1.5rem;
  }
  
  .join-community p {
    max-width: 100%;
  }
}

@media screen and (max-width: 576px) {
  .nav-bar header h1 {
    font-size: 1.8rem;
  }
  
  #Home {
    padding-top: 5rem;
  }
  
  .intro {
    width: 12rem;
    height: 2.2rem;
    font-size: 0.9rem;
  }
  
  .part1 h1 {
    font-size: 2rem;
  }
  
  .part1 p {
    font-size: 1rem;
  }
  
  .last1 button {
    width: 100%;
    margin-bottom: 1rem;
  }
  
  .about-content {
    gap: 3rem;
  }
  
  .about-mission p,
  .about-card p,
  .join-community p {
    font-size: 1rem;
  }
  
  .tech-item,
  .framework-item {
    height: auto;
    min-height: 200px;
  }
  
  .tech-logo,
  .framework-logo {
    width: 4rem;
    height: 4rem;
    font-size: 1.4rem;
  }
  
  .community-btn {
    width: 100%;
    padding: 0.8rem 1.5rem;
  }
}
</style>