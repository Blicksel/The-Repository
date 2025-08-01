# 📚 Blicksel Picks Admin Panel User Manual

Welcome to your content management system! This guide will help you manage all content on your website through the admin panel.

## 🚀 Getting Started

### Accessing the Admin Panel
1. **Visit**: https://picks.blicksel.com/admin
2. **Login**: Click "Login with GitHub"
3. **Authorize**: Grant permissions to access the repository
4. **Start Editing**: You're now in the admin dashboard!

### First Time Setup
- Make sure you have write access to the `Blicksel/Novo` GitHub repository
- Your changes will be saved as commits to the repository
- Published changes appear on the live site within 1-2 minutes

---

## 📝 Managing Blog Posts

### Creating a New Blog Post

1. **Navigate**: Go to "Blog Posts" in the sidebar
2. **Create**: Click "New Blog Posts"
3. **Fill Required Fields**:
   - **Title**: Your blog post title (e.g., "Best Gaming Headsets 2024")
   - **Description**: Brief summary for SEO and previews
   - **Featured Image**: Upload or paste image URL
   - **Category**: Select from dropdown (Electronics, Gaming, etc.)
   - **Tags**: Add relevant tags (comma-separated)
   - **Author**: Your name or "Blicksel Picks Team"
   - **Publish Date**: When to publish the post

4. **Optional Fields**:
   - **Featured Post**: Toggle to feature on homepage
   - **Amazon Button URL**: Add affiliate link for "Buy on Amazon" button
   - **Amazon Button Text**: Customize button text (default: "Buy on Amazon")

5. **Write Content**: Use the rich text editor for your article body
6. **Save**: Click "Save" to create draft or "Publish" to go live

### Editing Existing Posts

1. **Find Post**: Go to "Blog Posts" and click on any post
2. **Edit**: Make your changes
3. **Preview**: Use preview to see how it looks
4. **Update**: Click "Save" to update

### Blog Post Best Practices

#### SEO Optimization
- **Title**: Keep under 60 characters
- **Description**: 150-160 characters, include main keyword
- **Tags**: Use 3-5 relevant tags
- **Images**: Always include a featured image

#### Content Structure
```markdown
# Main Heading (H1)

Brief introduction paragraph.

## Section Heading (H2)

Content with **bold** and *italic* text.

### Subsection (H3)

- Bullet points
- For easy reading

## Conclusion

Wrap up your article.
```

#### Amazon Affiliate Integration
- **Amazon Button URL**: Paste your Amazon affiliate link
- **Button Text**: Customize (e.g., "Buy Gaming Headset", "Get This Deal")
- **In Content**: Use markdown links for inline affiliate links

---

## 🏷️ Managing Categories

### Creating New Categories

1. **Navigate**: Go to "Categories" in sidebar
2. **Create**: Click "New Categories"
3. **Fill Fields**:
   - **Category Name**: Display name (e.g., "Health & Fitness")
   - **URL Slug**: URL-friendly version (e.g., "health-fitness")
   - **Description**: What this category covers
   - **Icon**: Choose from available icons
   - **Color Class**: CSS class for styling
   - **Featured**: Toggle to show on homepage
   - **Product Count**: Number of products reviewed

4. **Content**: Write detailed category description in markdown
5. **Save**: Publish your new category

### Category Management Tips

#### URL Slugs
- Use lowercase letters only
- Replace spaces with hyphens
- No special characters except hyphens
- Examples: "smart-home", "health-fitness", "gaming"

#### Icons Available
- `smartphone` (Electronics)
- `home` (Smart Home)
- `utensils` (Kitchen)
- `heart` (Health & Fitness)
- `palette` (Beauty)
- `gamepad` (Gaming)
- `trophy` (Sports)

#### Color Classes
- `bg-blue-100 text-blue-800` (Blue theme)
- `bg-green-100 text-green-800` (Green theme)
- `bg-red-100 text-red-800` (Red theme)
- `bg-purple-100 text-purple-800` (Purple theme)
- `bg-orange-100 text-orange-800` (Orange theme)

---

## ⭐ Managing Product Reviews

### Creating Product Reviews

1. **Navigate**: Go to "Product Reviews"
2. **Create**: Click "New Product Reviews"
3. **Product Details**:
   - **Product Name**: Full product name
   - **Description**: Brief product summary
   - **Product Image**: High-quality product photo
   - **Category**: Select appropriate category
   - **Rating**: 1-5 stars (decimals allowed)
   - **Price**: Current price (e.g., "$149.99")
   - **Amazon URL**: Direct product link

4. **Review Details**:
   - **Pros**: List positive aspects (one per line)
   - **Cons**: List negative aspects (one per line)
   - **Best For**: Who should buy this (e.g., "Gamers", "Families")
   - **Author**: Reviewer name
   - **Publish Date**: Review date

5. **Content**: Write detailed review in markdown
6. **Amazon Integration**: Add affiliate links
7. **Publish**: Save and publish

### Review Writing Guidelines

#### Structure Your Review
```markdown
# Product Overview

Brief introduction to the product.

## Design and Build Quality

Physical aspects, materials, construction.

## Performance

How well it works, key features.

## Pros and Cons

### What We Love
✅ Feature 1
✅ Feature 2

### Areas for Improvement
❌ Issue 1
❌ Issue 2

## Final Verdict

Overall recommendation and rating explanation.
```

#### Rating Guidelines
- **5.0**: Exceptional, best in class
- **4.5-4.9**: Excellent with minor flaws
- **4.0-4.4**: Very good, solid choice
- **3.5-3.9**: Good with notable issues
- **3.0-3.4**: Average, consider alternatives
- **Below 3.0**: Not recommended

---

## 🏠 Managing Homepage Content

### Hero Section
1. **Navigate**: Go to "Homepage"
2. **Edit**: Click on "Homepage Content"
3. **Hero Section**:
   - **Title**: Main headline (use HTML for styling)
   - **Subtitle**: Supporting text
   - **Primary CTA**: Main button (text + URL)
   - **Secondary CTA**: Second button (text + URL)

### Featured Product Banner
- **Badge Text**: "PICK OF THE WEEK", "DEAL ALERT"
- **Badge Icon**: Choose icon (lightning, star, trophy)
- **Product Title**: Featured product name
- **Subtitle**: Deal information
- **Description**: Why it's featured
- **CTA Text**: Button text
- **CTA URL**: Amazon affiliate link
- **Price**: Current price

### Categories Section
- **Name**: Category display name
- **Icon**: Visual icon
- **Count**: Number of products
- **Color Class**: Styling theme
- **Description**: Brief category description

### Why Choose Us Section
- **Title**: Benefit headline
- **Description**: Detailed explanation
- **Icon**: Visual representation
- **Color Class**: Styling theme

### Statistics
- **Number**: Stat value (e.g., "500+")
- **Label**: What it represents
- **Icon**: Visual icon

---

## ⚙️ Site Settings

### General Settings
1. **Navigate**: Go to "Site Settings" → "General Settings"
2. **Update**:
   - **Site Title**: Your site name
   - **Site Description**: SEO description
   - **Site URL**: Your domain
   - **Contact Email**: Support email
   - **Social Media Links**: Facebook, Twitter, Instagram

### Navigation Management
1. **Go to**: "Navigation" → "Main Navigation"
2. **Header Links**:
   - **Name**: Menu item text
   - **URL**: Link destination
   - **Order**: Menu position (1, 2, 3...)

3. **Footer Links**:
   - **Quick Links**: Main footer navigation
   - **Legal Links**: Privacy, Terms, etc.

### Contact Information
1. **Navigate**: "Contact Information"
2. **Update**:
   - **Email**: Contact email
   - **Phone**: Optional phone number
   - **Address**: Optional physical address
   - **Social Media**: Social profiles
   - **Contact Form**: Enable/disable, subjects list

---

## 📄 Managing Pages

### About Page
1. **Navigate**: "Pages" → "About Page"
2. **Edit**: Update title, description, and content
3. **Content**: Write in markdown format

### Contact Page
1. **Navigate**: "Pages" → "Contact Page"
2. **Update**: Title, description, and page content

### Creating New Pages
Currently, new pages need to be created in the code. Contact your developer to add new static pages.

---

## 🎨 Content Best Practices

### Writing Guidelines

#### Headlines
- Use action words and benefits
- Keep under 60 characters for SEO
- Make them specific and compelling

#### Content Structure
- **Introduction**: Hook the reader
- **Body**: Break into digestible sections
- **Conclusion**: Summarize and call-to-action

#### SEO Tips
- Use keywords naturally in content
- Include internal links to other posts
- Add alt text to images
- Keep paragraphs short (2-3 sentences)

### Image Guidelines

#### Image Requirements
- **Format**: JPG or PNG
- **Size**: Minimum 800px wide
- **Quality**: High resolution, clear
- **Relevance**: Match your content

#### Image Sources
- **Pexels**: Free stock photos (recommended)
- **Unsplash**: Free high-quality images
- **Product Photos**: Official product images
- **Screenshots**: For tech reviews

#### Image URLs
When using external images, use this format:
```
https://images.pexels.com/photos/[ID]/pexels-photo-[ID].jpeg?auto=compress&cs=tinysrgb&w=800
```

### Amazon Affiliate Best Practices

#### Link Management
- Always use your affiliate tag
- Test links before publishing
- Update broken or expired links
- Use descriptive anchor text

#### Disclosure
- Always include affiliate disclosure
- Be transparent about commissions
- Follow FTC guidelines
- Maintain editorial independence

---

## 🔧 Troubleshooting

### Common Issues

#### "Page Not Found" Error
- Check your URL slug formatting
- Ensure no special characters
- Use lowercase and hyphens only

#### Images Not Loading
- Verify image URL is accessible
- Check image format (JPG/PNG)
- Ensure HTTPS URLs only

#### Changes Not Appearing
- Wait 1-2 minutes for deployment
- Clear browser cache
- Check if changes were saved

#### Login Issues
- Ensure GitHub access to repository
- Check internet connection
- Try incognito/private browsing

### Getting Help

#### Before Contacting Support
1. Clear browser cache
2. Try different browser
3. Check GitHub repository access
4. Verify internet connection

#### Contact Information
- **Email**: contact@blicksel-picks.com
- **GitHub Issues**: Create issue in repository
- **Documentation**: Refer to this manual

---

## 📊 Content Strategy Tips

### Editorial Calendar

#### Planning Content
- **Monday**: Product reviews
- **Wednesday**: Buying guides
- **Friday**: Deal alerts and news

#### Seasonal Content
- **January**: New Year tech deals
- **March**: Spring cleaning products
- **November**: Black Friday deals
- **December**: Holiday gift guides

### SEO Strategy

#### Keyword Research
- Use Google Keyword Planner
- Target long-tail keywords
- Focus on buyer intent keywords
- Monitor competitor content

#### Content Optimization
- Include target keyword in title
- Use keyword in first paragraph
- Add internal links to related posts
- Optimize images with alt text

### Social Media Integration

#### Content Promotion
- Share new posts on social media
- Create engaging post previews
- Use relevant hashtags
- Engage with your audience

#### Cross-Platform Strategy
- **Facebook**: Detailed posts with images
- **Twitter**: Quick updates and links
- **Instagram**: Visual product highlights
- **Pinterest**: Product collections

---

## 🚀 Advanced Features

### Markdown Formatting

#### Basic Formatting
```markdown
**Bold text**
*Italic text*
[Link text](https://example.com)
![Image alt text](image-url.jpg)
```

#### Lists
```markdown
- Unordered list item
- Another item

1. Ordered list item
2. Second item
```

#### Tables
```markdown
| Feature | Product A | Product B |
|---------|-----------|-----------|
| Price   | $99       | $149      |
| Rating  | 4.5/5     | 4.8/5     |
```

#### Code Blocks
```markdown
`inline code`

```
code block
```
```

### HTML in Markdown
You can use HTML for advanced formatting:
```html
<div class="highlight-box">
  <p>Special callout content</p>
</div>
```

### Custom Styling
Use CSS classes for special formatting:
- `highlight-box`: Yellow highlight background
- `pro-tip`: Green tip box
- `warning`: Red warning box

---

## 📈 Analytics and Performance

### Monitoring Success

#### Key Metrics
- **Page Views**: Track popular content
- **Time on Page**: Measure engagement
- **Bounce Rate**: Content relevance
- **Conversion Rate**: Affiliate link clicks

#### Content Performance
- Monitor which posts get most traffic
- Track affiliate link performance
- Analyze user engagement patterns
- Identify top-performing categories

### Optimization Tips

#### Content Updates
- Refresh old content regularly
- Update product prices and availability
- Add new information and features
- Improve SEO based on performance

#### Technical SEO
- Optimize page loading speed
- Ensure mobile responsiveness
- Fix broken links promptly
- Update meta descriptions

---

## 🎯 Quick Reference

### Essential Shortcuts

#### Admin Panel Navigation
- **Blog Posts**: Create and edit articles
- **Categories**: Manage product categories
- **Reviews**: Product review management
- **Homepage**: Update homepage content
- **Settings**: Site configuration

#### Content Creation Workflow
1. **Plan**: Research topic and keywords
2. **Create**: Write compelling content
3. **Optimize**: Add SEO elements
4. **Review**: Proofread and fact-check
5. **Publish**: Make live on site
6. **Promote**: Share on social media

#### Emergency Contacts
- **Technical Issues**: GitHub repository issues
- **Content Questions**: Refer to this manual
- **Urgent Problems**: contact@blicksel-picks.com

---

## 📚 Additional Resources

### Learning Resources
- **Markdown Guide**: https://www.markdownguide.org/
- **SEO Best Practices**: Google Search Console Help
- **Affiliate Marketing**: FTC Guidelines
- **Content Writing**: Copyblogger resources

### Tools and Extensions
- **Grammarly**: Grammar and spell checking
- **Hemingway Editor**: Readability improvement
- **Google Analytics**: Traffic monitoring
- **Ahrefs/SEMrush**: SEO analysis

### Community
- **GitHub Discussions**: Technical questions
- **Content Creator Groups**: Best practices
- **Affiliate Marketing Forums**: Strategy tips
- **SEO Communities**: Latest updates

---

*This manual is regularly updated. Last updated: January 2024*

**Happy content creating! 🚀**