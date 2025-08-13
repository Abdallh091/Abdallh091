<!-- Water-drop animated background + Typing intro in Sky-Blue -->
<div style="position: relative; overflow: hidden; padding: 18px 12px; border-radius:12px; background: linear-gradient(180deg, #02040a 0%, #071022 100%);">
  <!-- Animated droplet SVG as decorative background (subtle, non-intrusive) -->
  <div style="position: absolute; inset: 0; pointer-events: none; z-index: 0; display:flex; align-items:flex-start; justify-content:center;">
    <img alt="water-drop-animation"
         src='data:image/svg+xml;utf8,
         <svg xmlns="http://www.w3.org/2000/svg" width="800" height="300" viewBox="0 0 800 300" preserveAspectRatio="xMidYMid slice">
           <defs>
             <filter id="f1"><feGaussianBlur stdDeviation="6" /></filter>
             <radialGradient id="g1" cx="50%" cy="10%" r="40%">
               <stop offset="0%" stop-color="%2300CFFF" stop-opacity="0.35"/>
               <stop offset="60%" stop-color="%2300CFFF" stop-opacity="0.12"/>
               <stop offset="100%" stop-color="%2300CFFF" stop-opacity="0"/>
             </radialGradient>
           </defs>

           <!-- ripple group -->
           <g transform="translate(400,40)" opacity="0.9">
             <!-- droplet falling animation -->
             <path id="drop" d="M0,-10 C10,-30 30,-30 40,-10 C30,2 10,2 0,-10 Z" fill="%2300CFFF">
               <animateTransform attributeName="transform" type="translate" values="0 0; 0 140" dur="2.2s" repeatCount="indefinite" begin="0s"/>
               <animate attributeName="opacity" values="0;1;1;0" dur="2.2s" repeatCount="indefinite" begin="0s"/>
             </path>

             <!-- ripple (circle) -->
             <circle cx="20" cy="170" r="2" fill="%2300CFFF" opacity="0.18" filter="url(%23f1)">
               <animate attributeName="r" values="2;28" dur="2.2s" repeatCount="indefinite" begin="0.9s"/>
               <animate attributeName="opacity" values="0.35;0.18;0.06;0" dur="2.2s" repeatCount="indefinite" begin="0.9s"/>
             </circle>

             <circle cx="20" cy="170" r="1" fill="%2300CFFF" opacity="0.12">
               <animate attributeName="r" values="1;18" dur="2.2s" repeatCount="indefinite" begin="0.9s"/>
               <animate attributeName="opacity" values="0.25;0.12;0.04;0" dur="2.2s" repeatCount="indefinite" begin="0.9s"/>
             </circle>

             <!-- another drop offset for continuous effect -->
             <path d="M-80,-10 C-70,-30 -50,-30 -40,-10 C-50,2 -70,2 -80,-10 Z" fill="%2300CFFF" opacity="0.7">
               <animateTransform attributeName="transform" type="translate" values="0 0; 0 150" dur="3.0s" repeatCount="indefinite" begin="1.1s"/>
               <animate attributeName="opacity" values="0;0.7;0.7;0" dur="3.0s" repeatCount="indefinite" begin="1.1s"/>
             </path>
           </g>

           <!-- subtle top-to-bottom gradient overlay to blend -->
           <rect x="0" y="0" width="800" height="300" fill="url(%23g1)" />
         </svg>'
         style="width:120%; opacity:0.18; transform: translateY(-10%);"
    />
  </div>

  <!-- Content sits above the SVG -->
  <div style="position: relative; z-index: 2; color: #d7eefb; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;">

    <!-- Typing SVG: name included and sky-blue color -->
    <p align="center" style="margin: 6px 0 12px 0;">
      <img src="https://readme-typing-svg.demolab.com?font=Inter&pause=900&center=true&vCenter=true&width=760&height=60&lines=Hi+%F0%9F%91%8B%2C+I'm+Abdalluh+Nasser+Ahmed+Mansour;Frontend+Developer+%7C+React+%7C+Vue+%7C+GSAP;I+build+smooth%2C+responsive+experiences&color=%2300CFFF"
           alt="typing" />
    </p>

    <!-- The list you provided, restyled with sky-blue bullets -->
    <div style="font-size:15px; line-height:1.6; color:#dcedff; max-width:820px; margin: 0 auto;">
- <span style="color:#00CFFF; font-weight:600;">🔭 I’m currently working on</span> Building responsive websites for small businesses and startups  
- <span style="color:#00CFFF; font-weight:600;">🌱 I’m currently learning</span> Advanced React hooks, Tailwind CSS, and TypeScript  
- <span style="color:#00CFFF; font-weight:600;">👯 I’m looking to collaborate on</span> Innovative frontend projects using React or Vue  
- <span style="color:#00CFFF; font-weight:600;">🤝 I’m looking for help with</span> Optimizing web app performance and UI/UX improvements  
- <span style="color:#00CFFF; font-weight:600;">👨‍💻 All of my projects are available at</span> <a href="https://github.com/your-Abdallh091" target="_blank" rel="noreferrer" style="color:#9fe8ff; text-decoration:underline;">https://github.com/your-Abdallh091</a>  
- <span style="color:#00CFFF; font-weight:600;">💬 Ask me about</span> React, Vue, GSAP, and creating smooth animations  
- <span style="color:#00CFFF; font-weight:600;">📫 How to reach me</span> <a href="mailto:abdallhnasser2025@gmail.com" style="color:#9fe8ff; text-decoration:underline;">abdallhnasser2025@gmail.com</a>  
- <span style="color:#00CFFF; font-weight:600;">⚡ Fun fact</span> I love experimenting with CSS art and animations!
    </div>

  </div>
</div>

<!-- small spacer -->
<p></p>