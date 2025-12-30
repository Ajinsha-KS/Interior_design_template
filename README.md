# AESTUDIO - Interior Design Website 🏠

A modern, elegant interior design website showcasing professional design services, projects, and team members. Built with pure HTML and CSS, featuring smooth animations, hover effects, and a sophisticated layout.

## 🎨 Project Overview

AESTUDIO is a single-page website for an interior design firm established in 1990. The site presents a complete portfolio of services, project galleries, designer profiles, and customer testimonials with a focus on sustainability and innovation.

## ✨ Features

### Homepage (Hero Section)
- **Animated Hero Banner**: Gradient background with sliding text animations
- **Tagline**: "Designing Spaces, Defining You"
- **Feature Highlights**: Crafted Furniture, Sustainable Materials, Innovative Architects, Budget Friendly
- **Hero Image**: Decorative image with smooth fade-in animation

### About Section (Page 2)
- **Company History**: Dual-image layout with award showcase
- **Timeline**: "Award Winning Studio Since 1990"
- **Key Features Grid**: Award Winning, 24/7 Support, Professional Staff, Fair Prices
- **Social Media Integration**: Facebook, Instagram, X (Twitter), YouTube, Email

### Why Choose Us (Page 3)
- **6 Service Cards** arranged in a 2-row grid:
  - 25+ Years Experience
  - Best Interior Design
  - Innovative Architects
  - Customer Satisfaction
  - Budget Friendly
  - Sustainable Material
- Icon-based presentation with detailed descriptions

### Projects Gallery (Page 4)
- **1000+ Projects Showcase**
- **6-Image Grid Layout**:
  - Kitchen designs
  - Bathroom renovations
  - Bedroom interiors
  - Living room spaces
  - Furniture collections
  - Complete home projects
- **Hover Effects**: Image zoom on hover

### Services Section (Page 5)
- **Creative Services Description**
- **24/7 Contact Widget**: Phone number with call-to-action
- **4-Service Grid** with alternating color scheme:
  - Interior Design
  - Implementation
  - Renovation
  - Commercial Design
- **Interactive Hover Effects**: Color inversion on hover

### Team Section (Page 6)
- **Professional Designers Showcase**
- **4 Team Members**:
  - Ellie Charlotte - Architect
  - Faheem Shah - 3D Visualizer
  - Leo Henry - Interior Designer
  - Alana King - Project Manager
- Clean card layout with photos and titles

### Testimonials (Page 7)
- **Customer Satisfaction Section**
- Featured testimonial from Clive Donald
- Decorative image with gradient background box
- Rotating image effect on hover

### Newsletter (Page 8)
- **Email Subscription Form**
- "Subscribe the Newsletter" call-to-action
- Background image with overlay
- Styled input and submit button

### Footer
- **4-Column Layout**:
  - About AESTUDIO
  - Get In Touch (contact information)
  - Popular Links
  - Our Services
- **Social Media Icons**
- **Copyright Information**
- Hover effects on links with scale transformation

## 🎨 Design Features

### Color Palette
- **Primary Green**: `rgb(2, 70, 2)` / `darkgreen`
- **Dark Green Accent**: `rgb(1, 37, 1)` / `rgb(1, 49, 1)`
- **Light Green Background**: `rgb(229, 247, 229)`
- **Text Colors**: `darkslategray`, `lightslategray`
- **White Accents**: For contrast and readability

### Typography
- **Primary Font**: Lucida Sans family
- **Heading Font**: Courier New (logo), Gill Sans (projects)
- **Body Font**: Lucida Sans, Cambria
- **Font Sizes**: Responsive scaling from 10px to 4rem

### Animations
- **Hero Text Animation**: Slide-in from left with fade
- **Hero Image Animation**: Slide-in from right with fade
- **Hover Transformations**: Scale effects (1.1x zoom)
- **Rotation Effects**: 3-degree rotation on testimonial image
- **Smooth Transitions**: 0.4s - 2s duration

## 🛠️ Technologies Used

- **HTML5** - Semantic structure and content
- **CSS3** - Advanced styling and animations
  - Flexbox for layout alignment
  - CSS Grid for card layouts
  - CSS Animations and Keyframes
  - Gradient backgrounds
  - Transform and Transition effects
  - Hover states and pseudo-classes
  - Position absolute/relative for overlays

## 📁 Project Structure

```
interior-design/
├── project.html              # Main HTML file
├── project.css              # Stylesheet
├── images/                  # Image assets
│   ├── logo.png
│   ├── bg4.jpg             # Hero background
│   ├── decor.jpg, decor1.jpg, decor2.jpg
│   ├── kitchen.jpg
│   ├── bathroom.jpg
│   ├── bedroom.jpg
│   ├── living.jpg
│   ├── furniture.jpg
│   ├── home.jpg
│   ├── design1.jpg - design4.jpg
│   ├── designer1.jpg - designer4.jpg
│   ├── customer.jpg
│   ├── last.jpg
│   └── icons/
│       ├── facebook.svg
│       ├── instagram.svg
│       ├── x.svg
│       ├── youtube.svg
│       ├── mail.svg
│       ├── calender.svg
│       ├── list.svg
│       ├── draw.svg
│       ├── user.svg
│       ├── money-bag.svg
│       ├── tick.svg
│       └── call.svg
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor for code viewing/editing (VS Code, Sublime Text)

### Installation

1. **Clone or download the project**
```bash
git clone <repository-url>
cd interior-design
```

2. **Open the project**
```bash
# Double-click project.html or open via command line

# Windows
start project.html

# macOS
open project.html

# Linux
xdg-open project.html
```

3. **Ensure all images are in the correct folder**
   - Place all images in an `images/` folder
   - Verify image paths match the HTML references

## 📱 Page Sections Breakdown

### Section 1: Navigation & Hero
- Fixed navigation bar with logo and menu items
- Full-screen hero section with animated content
- Background image with overlay

### Section 2: Company History
- Two-column layout with images and text
- Award badge and timeline
- Feature checkmarks
- Social media links

### Section 3: Services Grid
- 6 feature boxes in 3x2 grid
- Icon-based design
- Consistent spacing and alignment

### Section 4: Projects Gallery
- Large showcase banner
- 3x2 image grid
- Hover zoom effects
- Project counter: "1000+ Projects"

### Section 5: Services Details
- Split layout: content left, services grid right
- Contact widget with phone number
- 2x2 service cards with images
- Interactive color-swap hover effects

### Section 6: Team Profiles
- 4-column designer showcase
- Professional headshots
- Name and role descriptions
- Light green background section

### Section 7: Testimonial
- Image with decorative overlay
- Customer quote and name
- Side-by-side layout

### Section 8: Newsletter
- Email subscription form
- Background image
- Call-to-action button

### Section 9: Footer
- Multi-column layout
- Contact information
- Quick links
- Social media icons
- Copyright notice

## 🎯 CSS Techniques Demonstrated

### Layout Techniques
- **Flexbox**: Navigation, content sections, footer
- **CSS Grid**: Service cards, project gallery
- **Positioning**: Absolute positioning for image overlays
- **Fixed Navigation**: Sticky header (if implemented)

### Visual Effects
- **Linear Gradients**: Background boxes and sections
- **Box Shadows**: Card depth (if added)
- **Border Radius**: Rounded corners
- **Opacity Transitions**: Fade effects
- **Transform Properties**: Scale, rotate, translate

### Animations
- **Keyframe Animations**: 
  - `@keyframes moving` - Slide from left
  - `@keyframes moving2` - Content fade-in
  - `@keyframes moving3` - Image slide-in
- **Hover Transitions**: Color changes, scaling
- **Transform Origins**: Center-based transformations

### Responsive Elements
- Flexible widths with percentages
- Min-height for full viewport coverage
- Auto-sizing images
- Fluid typography

## 🌟 Key Features

### Interactive Elements
- Navigation hover effects with color change
- Project image zoom on hover
- Service cards with color inversion
- Social media icon interactions
- Form input styling
- Link transformations

### Professional Design
- Consistent color scheme
- Generous white space
- Clear visual hierarchy
- Professional photography
- Icon-based communication
- Branded color palette

### Content Organization
- Logical section flow
- Clear CTAs (Call-to-Actions)
- Contact information accessibility
- Service descriptions
- Team credentials
- Social proof (testimonials)

## 🔮 Future Enhancements

- [ ] Add responsive media queries for mobile devices
- [ ] Implement JavaScript for form validation
- [ ] Add smooth scroll navigation
- [ ] Create image lightbox/modal for gallery
- [ ] Add loading animations
- [ ] Implement lazy loading for images
- [ ] Create a contact form with backend integration
- [ ] Add more page transitions
- [ ] Implement hamburger menu for mobile
- [ ] Add animation triggers on scroll
- [ ] Create additional pages (About, Services detail, Projects detail)
- [ ] Add client logo carousel
- [ ] Implement before/after project sliders

## 📊 Performance Considerations

- Optimize image sizes for web
- Minimize CSS for production
- Consider lazy loading for images
- Use responsive images
- Implement caching strategies

## 📄 License

This project is created for portfolio and educational purposes.

## 👤 Author

**Ajinsha**
- Design and Development

## 🙏 Acknowledgments

- Icon designs from SVG sources
- Professional photography for project showcases
- Inspiration from modern interior design websites
- Color palette influenced by nature and sustainability themes

---

**AESTUDIO** - Designing Spaces, Defining You Since 1990 ✨
