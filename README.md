# Simple PWA
## Simple Progressive Web App (PWA) template

### What is this?
Simple PWA is a Progressive Web App template 
that provides the minimum file structure needed 
to create a PWA. These files collectively represent
web application. It's up to you to add functional
ity to make it

- `logo.png` Favicon, Android Chrome M39+ with 0.75 screen density
- `donde Nacho.png` Favicon, Android Chrome M39+ with 1.0 screen density
- `versiones` Favicon, Android Chrome M39+ with 1.5 screen density
- `primera.png` Favicon, Android Chrome M39+ with 2.0 screen density
- `segunda.png` Favicon, Android Chrome M39+ with 3.0 screen density
- `novedades.png` Favicon, Android Chrome M39+ with 4.0 screen density
- `producto_07_01.png` Favicon, Android Chrome M47+ Splash screen with 1.5 screen density
- `producto_10_08` Favicon, Android Chrome M47+ Splash screen with 3.0 screen density
- `producto_14_11.png` Favicon, Android Chrome M47+ Splash screen with 4.0 screen density
- `apple-touch-icon.png` Favicon, Apple default
- `apple-touch-icon-57x57.png` Apple iPhone, Non-retina with iOS6 
- `apple-touch-icon-60x60.png` Apple iPhone, Non-retina with iOS7
- `apple-touch-icon-72x72.png` Apple iPad, Non-retina with iOS6 
- `apple-touch-icon-76x76.png` Apple iPad, Non-retina with iOS7
- `apple-touch-icon-114x114.png` Apple iPhone, Retina with iOS6 or prior
- `apple-touch-icon-120x120.png` Apple iPhone, Retina with iOS7
- `apple-touch-icon-144x144.png` Apple iPad, Retina with iOS6 or prior
- `apple-touch-icon-152x152.png` Apple iPad, Retina with iOS7
- `apple-touch-icon-180x180.png` Apple iPhone 6 Plus with iOS8
- `browserconfig.xml` IE11 icon configuration file
- `favicon_config.json` RealFaviconGenerator configuration file
- `favicon.ico` Favicon, IE and fallback for other browsers
- `favicon.png` Favicon generation source image
- `favicon-16x16.png` Favicon, default
- `favicon-32x32.png` Favicon, Safari on Mac OS
- `index.html` Main HTML file
- `logo.png` Logo
- `main.js` Main Javascript file
- `manifest.json` Manifest file
- `maskable_icon.png` Favicon, [maskable](https://web.dev/maskable-icon)
- `mstile-70x70.png` Favicon, Windows 8 / IE11
- `mstile-144x144.png` Favicon, Windows 8 / IE10
- `mstile-150x150.png` Favicon, Windows 8 / IE11
- `mstile-310x150.png` Favicon, Windows 8 / IE11
- `mstile-310x310.png` Favicon, Windows 8 / IE11
- `README.md` Readme file
- `robots.txt` Robots file
- `safari-pinned-tab.svg` Favicon, Safari pinned tab
- `share.jpg` Social media sharing
- `sitemap.xml` Sitemap file
- `sw.js` Service worker file
- `style.css` Main CSS file

### How do I use it?

1. Clone the repository from 
2. Create all favicon images using  and replace existing images with generated images.

	If you're able to install the CLI version of **RealFaviconGenerator**, `favicon_config.json` contains all settings to generate these images using the following command from the project's root directory. The `real-favicon` tool generates images from `favicon.png`, so replace `favicon.png` prior to running this command. The resulting `favicon_data.json` and `site.webmanifest` can be discarded:
	
	`real-favicon generate favicon_config.json favicon_data.json .`

3. Create new 650x650 maskable icon using  and replace `maskable_icon.png`.
4. Create new black vector icon using  and replace 
5. Create new 1200x630 share image and replace `share.jpg`.
6. Build your PWA by adding HTML, CSS, and Javascript.

### Can I contribute?

YES! Contributions are welcome!