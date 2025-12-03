🚀 Speedy Tech Link - Cyberpunk IT Website

A cyberpunk-themed single-page website for Speedy Tech Link IT services, featuring neon aesthetics, circuit board backgrounds, and a responsive design.

https://speedytechlink.com
🌐 Live Demo

View Live Site • GitHub Repository
✨ Features

    🎮 Cyberpunk Aesthetic: Neon borders, circuit board background, terminal fonts

    📱 Fully Responsive: Works on all devices from mobile to desktop

    📧 Contact Form: Integrated FormSubmit.io with ad-blocker detection

    ⚡ Performance Optimized: Minimal dependencies, optimized animations

    🎨 Custom Branding: Dark green/neon color scheme matching business identity

🛠️ Technologies Used

    HTML5 - Semantic markup

    CSS3 - Custom cyberpunk styling with animations

    JavaScript - Form handling and interactive elements

    Font Awesome - Icons

    Google Fonts - IBM Plex Mono font

    FormSubmit.io - Form backend service

🚀 Quick Start
Option 1: Deploy to GitHub Pages

    Fork this repository

    Go to Repository Settings → Pages

    Set source to "main branch"

    Your site will be live at: https://yourusername.github.io/speedy-tech-link/

Option 2: Use with Google Sites

    Copy the entire HTML from index.html

    Paste into a Google Sites HTML box

    Update image URLs if needed

Option 3: Self-Host

    Clone the repository

    Upload to your web hosting

    Update form email in line 356 of HTML

⚙️ Configuration
Update Contact Information

Edit these lines in index.html:
html

Line 356: action="https://formsubmit.io/send/YOUR_EMAIL_HERE"
Line 594: <a href="tel:YOUR_PHONE_HERE">
Line 598: <a href="mailto:YOUR_EMAIL_HERE">

Customize Colors

Edit CSS variables in the <style> section:
css

:root {
    --neon-green: #00ff99;      /* Primary neon color */
    --neon-pink: #ff00cc;       /* Accent color */
    --neon-blue: #00ccff;       /* Secondary color */
    --dark-bg: #0a0a0a;         /* Background color */
}

Update Services

Edit the services list in the HTML:
html

<ul class="services">
    <li>Your Service 1</li>
    <li>Your Service 2</li>
    <!-- Add more services here -->
</ul>

📧 Form Configuration

The contact form uses FormSubmit.io as backend. To set up:

    Default Setup (Already configured):

        Form submissions go to: ryan@speedytechlink.com

        Auto-reply message included

        Spam protection enabled

    Customize FormSubmit:

        Visit FormSubmit.io

        Create account for analytics

        Generate your own endpoint if needed

    Form Features:

        ✅ Ad-blocker detection with fallback

        ✅ Email validation

        ✅ Loading states

        ✅ Success/error messages

        ✅ Direct email fallback option

🎨 Design Features
Cyberpunk Elements

    Animated neon borders (top, bottom, sides)

    Circuit board background with overlay

    Scanline effect for CRT monitor feel

    Terminal-style blinking cursor

    Grid overlay for tech aesthetic

Responsive Breakpoints

    Desktop: 1200px+ (Full features)

    Tablet: 768px-1199px (Adaptive layout)

    Mobile: 480px-767px (Stacked layout)

    Small Mobile: <480px (Optimized touch)

Interactive Elements

    Hover effects on service items

    Smooth scroll animations

    Form validation feedback

    Click-to-call/email buttons

🔧 Troubleshooting
Common Issues

    Form not submitting:

        Check ad-blocker is disabled

        Verify email in form action is correct

        Test with direct email fallback button

    Images not loading:

        Check image file paths in assets/ folder

        Verify file permissions

        Ensure correct file extensions (.png, .jpg)

    Styles not applying:

        Clear browser cache (Ctrl+F5)

        Check CSS is properly linked

        Verify no syntax errors in console

    Mobile layout issues:

        Check viewport meta tag is present

        Test on actual mobile device

        Use browser developer tools mobile view

Browser Compatibility

    ✅ Chrome 60+

    ✅ Firefox 55+

    ✅ Safari 12+

    ✅ Edge 79+

    ✅ Mobile browsers

📱 Mobile Optimization

The site includes:

    Touch-friendly buttons (min 44px touch targets)

    Responsive font sizes (clamp() function)

    Mobile-first media queries

    Optimized image loading

    Reduced animations on mobile for performance

🔒 Security Features

    Form spam protection (honeypot field)

    Email validation

    HTTPS ready

    No external tracking scripts

    Minimal third-party dependencies

📊 Performance
Optimizations:

    Inline critical CSS

    Deferred JavaScript loading

    Optimized image formats

    Minimal HTTP requests

    CSS animations (GPU accelerated)

Lighthouse Score Target:

    Performance: 95+

    Accessibility: 100

    Best Practices: 100

    SEO: 100

🌐 SEO Features

    Semantic HTML5 markup

    Mobile-responsive design

    Fast loading times

    Proper meta tags

    Clean URL structure

    Social media meta tags

📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
🤝 Contributing

    Fork the project

    Create your feature branch (git checkout -b feature/AmazingFeature)

    Commit your changes (git commit -m 'Add some AmazingFeature')

    Push to the branch (git push origin feature/AmazingFeature)

    Open a Pull Request

📞 Support

For support or questions:

    Email: ryan@speedytechlink.com

    Phone: 0410 583 525

    Create an issue

🚀 Deployment Notes
GitHub Pages Deployment
bash

# Clone repository
git clone https://github.com/yourusername/speedy-tech-link.git

# Deploy to GitHub Pages
# 1. Push to main branch
# 2. Enable GitHub Pages in settings
# 3. Site will deploy automatically

Custom Domain Setup (Optional)

    Add CNAME file with your domain

    Update DNS settings with your registrar

    Configure GitHub Pages custom domain in settings

🔄 Updates & Maintenance
Regular Maintenance Tasks:

    Update contact information as needed

    Refresh services list quarterly

    Test form functionality monthly

    Update dependencies as needed

    Check browser compatibility annually

Version History:

    v1.0.0 (Current): Initial release with cyberpunk theme

    Planned: Add portfolio section, client testimonials

Built with ❤️ for Speedy Tech Link • Perth NOR IT Services • © 2023
📋 Changelog
v1.0.0 - Initial Release

    Complete cyberpunk-themed website

    Responsive design for all devices

    Working contact form with FormSubmit.io

    Ad-blocker detection and fallbacks

    Performance optimizations

    Mobile-first approach

This README is part of the Speedy Tech Link website project. For business inquiries, contact ryan@speedytechlink.com.
