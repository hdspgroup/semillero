# HDSP Research Group Website

This repository contains the source code for the HDSP (High Dimensional Signal Processing) Research Group website at Universidad Industrial de Santander (UIS), Colombia.

## About HDSP

The HDSP Research Group focuses on high-dimensional signal processing, compressed sensing, and computational imaging. Led by Professor Henry Arguello, the group explores cutting-edge research in:

- Statistical signal processing
- Super-resolution techniques
- Inverse problems
- Optical imaging
- Video processing
- Hyperspectral imaging
- Compressive sensing

In the last 40 years, developments in sensing, analysis, and processing of digital signals have grown considerably. The HDSP group is at the forefront of this revolution, particularly in areas where compressed sensing theory has challenged the well-known Nyquist theory, enabling new applications in microscopy, radar, holography, and tomography.

## Website Structure

This site is built using Jekyll and is hosted on GitHub Pages. The site includes:

- **Home**: Welcome page with an introduction to HDSP
- **People**: Research team members including professors, doctoral students, master students, and undergraduate students
- **Writing**: Blog posts and research updates
- **Contact**: Contact information and location details

## Local Development

### Prerequisites

- Ruby (version 2.5 or higher)
- RubyGems
- Jekyll
- Bundler

### Installation

1. Clone this repository:
```bash
git clone https://github.com/hdspgroup/semillero.git
cd semillero
```

2. Install dependencies:
```bash
bundle install
```

3. Run the site locally:
```bash
jekyll serve
```

4. Open your browser and navigate to [http://localhost:4000](http://localhost:4000)

## Adding Content

### Adding a New Post

1. Create a new file in the `_posts` directory following the naming convention: `YYYY-MM-DD-title.md`
2. Add the following front matter at the top of the file:

```yaml
---
layout: post
title: "Your Post Title"
author: "Author Name"
categories: journal
tags: [tag1, tag2]
image: image-filename.jpg
---
```

3. Write your content in Markdown format below the front matter

### Adding a New Menu Page

1. Create a new `.md` file in the `menu` directory
2. Add the page to the menu by editing `_data/settings.yml`

## Configuration

### Site Settings

Edit `_config.yml` to modify:
- Site title and description
- Author information
- Build settings and plugins

### Theme Settings

Edit `_data/settings.yml` to customize:
- Menu items
- Social media links
- Disqus comments (if enabled)
- Google Analytics ID

## Contributing

We welcome contributions from the research community! If you'd like to contribute:

1. Fork the repository
2. Create a new branch for your feature (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

Please ensure your code follows the existing style and conventions.

## Contact

**HDSP Research Group**  
Carrera 27, Calle 9, Edificio. LP, Of. 333, 334 and 336  
Escuela de Ingeniería de Sistemas e Informática  
Universidad Industrial de Santander, 680002  
Bucaramanga, Colombia

**Email**: hdsp [AT] uis.edu.co | henarfu [AT] uis.edu.co  
**Phone**: +57-607-6344000 Ext: 2476 or 2676

**Website**: [https://hdspgroup.github.io/semillero/](https://hdspgroup.github.io/semillero/)  
**GitHub**: [https://github.com/hdspgroup](https://github.com/hdspgroup)  
**LinkedIn**: [Professor Henry Arguello](https://www.linkedin.com/in/henry-arguello-2905929/)  
**Instagram**: [@hdspgroup](https://www.instagram.com/hdspgroup/)

## Credits

This website is built using the [Lagrange](https://github.com/LeNPaul/Lagrange) Jekyll theme by Paul Le.

## License

This project is open source and available under the [MIT License](LICENSE.md).
