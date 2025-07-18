# You Are Stardust ✨

A beautiful, cosmic-themed web application that combines NASA's Astronomy Picture of the Day with inspirational content about our stellar origins. This project reminds visitors that we are literally made of stardust - elements forged in the hearts of ancient stars.

## What It Does

**You Are Stardust** displays stunning astronomy images from NASA's APOD (Astronomy Picture of the Day) API alongside educational content about stellar nucleosynthesis - the process by which stars create the elements that make up our bodies. Each visit shows a different cosmic view while telling the story of how we're all connected to the universe.

## Features

- 🌟 **NASA APOD Integration**: Fetches and displays random astronomy images from NASA's archive
- 🔑 **API Key Management**: Supports both demo keys and personal NASA API keys with local storage
- ✨ **Animated Particle Background**: Twinkling stars create an immersive cosmic atmosphere  
- 📱 **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- 🖼️ **High-Resolution Links**: Click images to view full-resolution versions
- ⚡ **Smart Error Handling**: Graceful fallbacks for API limits, network issues, and non-image content
- 🎨 **Modern UI**: Built with Tailwind CSS for a sleek, professional appearance
- 💾 **Persistent Settings**: API keys are saved locally for convenience

## How to Use

1. **Open the Application**: Simply open `index.html` in any modern web browser
2. **Get a NASA API Key** (optional but recommended):
   - Visit [api.nasa.gov](https://api.nasa.gov/) to get your free API key
   - Enter your key in the input field and click "Save Key"
   - This removes rate limits compared to the demo key
3. **Explore**: Click "Explore Another Cosmic View" to see different astronomy images
4. **Learn**: Read about how the elements in your body were created in distant stars
5. **Share**: Click on any image to view the full-resolution version

## Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript (no frameworks required)
- **Styling**: Tailwind CSS via CDN
- **Fonts**: Inter font family from Google Fonts
- **API**: NASA APOD API for astronomy images
- **Storage**: Browser localStorage for API key persistence
- **Animations**: CSS keyframes for particles and transitions

## File Structure

```
stardust/
├── index.html          # Complete single-file application
├── README.md          # This file
└── LICENSE            # Project license
```

## Browser Support

Works in all modern browsers that support:
- ES6 JavaScript features
- CSS Grid and Flexbox
- Local Storage API
- Fetch API

## NASA API Information

- **Demo Key**: Limited to 30 requests per hour per IP
- **Personal Key**: Up to 1,000 requests per hour
- **Get Your Key**: Free at [api.nasa.gov](https://api.nasa.gov/)
- **Documentation**: [NASA APOD API Docs](https://github.com/nasa/apod-api)

## Educational Content

The application teaches visitors about:
- **Stellar Nucleosynthesis**: How stars forge heavy elements
- **Supernovae**: Stellar explosions that distribute elements across space
- **Big Bang Nucleosynthesis**: Origin of hydrogen and helium
- **Cosmic Evolution**: How stardust becomes planets and life

## License

This project is open source. See the LICENSE file for details.

---

*"The nitrogen in our DNA, the calcium in our teeth, the iron in our blood, the carbon in our apple pies were made in the interiors of collapsing stars. We are made of star stuff."* - Carl Sagan
