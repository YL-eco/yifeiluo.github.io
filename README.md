
# Yifei Luo - Personal Academic Website

This is the source code for my personal academic website, built with Jekyll and hosted on GitHub Pages.

## 🌐 Website Features

- **Modern Design**: Clean, professional layout with responsive design
- **Research Showcase**: Detailed presentation of working papers and research projects
- **Academic Profile**: Comprehensive bio, CV, and contact information
- **Code Repository**: Documentation of research software and technical skills
- **Mobile Responsive**: Optimized for all device sizes

## 🛠️ Technical Stack

- **Framework**: Jekyll (static site generator)
- **Theme**: Minimal theme with custom styling
- **Hosting**: GitHub Pages
- **CSS**: Custom modern styling with animations and hover effects
- **Icons**: Emoji icons for visual appeal

## 📁 Project Structure

```
yifeiluo.github.io/
├── _config.yml          # Jekyll configuration
├── _includes/           # Reusable HTML components
│   ├── head-custom.html # Custom head tags and CSS
│   └── nav.html         # Navigation menu
├── assets/              # Static assets
│   ├── css/
│   │   └── style.css    # Custom CSS styles
│   ├── cv/
│   │   └── yifei_luo_cv.pdf
│   └── img/
│       └── profile.jpg
├── index.md             # Homepage
├── bio.md              # About page
├── research.md         # Research papers
├── cv.md              # CV page
└── code.md            # Code and software
```

## 🎨 Design Features

### Color Scheme
- Primary: Blue (#3498db)
- Secondary: Dark blue (#2c3e50)
- Accent: Red (#e74c3c)
- Background: Light gray (#f8f9fa)

### Typography
- Modern system fonts for optimal readability
- Clear hierarchy with different heading sizes
- Responsive text scaling

### Interactive Elements
- Hover effects on cards and buttons
- Smooth transitions and animations
- Expandable content sections
- Professional navigation with gradient background

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop computers (1200px+)
- Tablets (768px - 1199px)
- Mobile phones (up to 767px)

## 🔧 Customization

### Adding New Pages
1. Create a new `.md` file in the root directory
2. Add the Jekyll front matter:
   ```yaml
   ---
   layout: default
   title: Page Title
   permalink: /page-url
   ---
   ```
3. Include the navigation: `{% include nav.html %}`
4. Use the CSS classes for consistent styling

### Updating Content
- **Research**: Edit `research.md` to add new papers
- **Bio**: Update `bio.md` with new information
- **CV**: Replace the PDF file in `assets/cv/`
- **Code**: Add new projects to `code.md`

### Styling Changes
- Main styles are in `assets/css/style.css`
- The design uses CSS Grid and Flexbox for layout
- Animations are defined with CSS keyframes

## 🚀 Deployment

The website is automatically deployed via GitHub Pages:
1. Push changes to the `main` branch
2. GitHub Pages will automatically rebuild and deploy
3. Changes are typically live within 5-10 minutes

## 📊 Analytics and SEO

- **SEO**: Optimized meta tags and structured data
- **Social Media**: Open Graph and Twitter Card support
- **Performance**: Optimized images and CSS
- **Accessibility**: Semantic HTML and proper contrast ratios

## 🔗 External Links

- **SSRN Profile**: https://ssrn.com/author=6801941
- **GitHub**: https://github.com/yifeiluo
- **Email**: luoyifei426@gmail.com

## 📝 License

This website is open source and available under the MIT License.

## 🤝 Contributing

While this is a personal website, suggestions and improvements are welcome. Please feel free to:
- Report bugs or issues
- Suggest design improvements
- Propose new features

---

*Last updated: {{ site.time | date: "%B %d, %Y" }}*
