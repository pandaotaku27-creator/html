# 💕 Be My Valentine 💕

A cute, interactive Valentine's Day proposal website with animations, confetti, balloons, and adorable bunny aesthetic!

## Features ✨

- 🎨 **Cute Bunny Aesthetic**: Pastel gradient background with floating bunnies and flowers
- 🎬 **Interactive Slides**: Progressive proposal with 4 different questions
- 😸 **Cute Cat Popup**: A happy cat that appears when you say YES
- 🤗 **Adorable Hug Animation**: Sweet hug display after acceptance
- ⚠️ **NO Button Logic**: 
  - First 2 times: "No" button disables and reduces opacity
  - Third time: Shows a playful warning message
- 🎵 **Music Support**: Add your favorite "Blue" song (Joni Mitchell, Billie Eilish, etc.)
- 🎉 **Celebration Effects**: Confetti, balloons, and animations
- 🌐 **Publicly Accessible**: Deployed via GitHub Pages - no login required!

## How to Use 🎯

### Online
Your valentine can visit the site directly via GitHub Pages without any login:
```
https://pandaotaku27-creator.github.io/html/valentines-day.html
```

### Locally
1. Clone the repository
2. Open `valentines-day.html` in your web browser
3. Click "Yes" to proceed through the proposal! 💕

## Customization 🎨

### Add Your Own Music
To add your favorite "Blue" song:

1. **Option 1 - Upload to Google Drive:**
   - Upload your Blue song to Google Drive
   - Right-click → Share → Change to "Anyone with the link"
   - Get the sharing link and extract the file ID
   - Create an embeddable link: `https://drive.google.com/uc?export=play&id=YOUR_FILE_ID`

2. **Option 2 - Use Dropbox:**
   - Upload your music to Dropbox
   - Get the sharing link
   - Change `dl=0` to `dl=1` at the end
   - Use as the audio source

3. **Option 3 - Other Hosting:**
   - Use any music hosting service that provides direct links
   - Visit [YouTube to MP3 converters](https://www.youtube-mp3.online/) if converting from YouTube

4. **Update the HTML:**
   - Open `valentines-day.html`
   - Find the `<audio>` element with the `<source>` tag
   - Replace the `src` URL with your music file link:
   ```html
   <source src="YOUR_MUSIC_URL_HERE" type="audio/mpeg">
   ```

### Customize Messages
Edit the card content in HTML to personalize:
- Change the questions/messages
- Update emojis
- Modify button text

## Deployment 🚀

The site is automatically deployed to GitHub Pages! 

### To ensure it's public:
1. Go to repository Settings → Pages
2. Source: Deploy from a branch
3. Branch: main
4. Folder: / (root)
5. Save

Your link will be live at: `https://YOUR_USERNAME.github.io/html/valentines-day.html`

## Browser Support 🌐

Works on all modern browsers:
- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## Made with 💖

Perfect for Valentine's Day proposals, anniversary celebrations, or just expressing your love! 🥰

---

**Share the link with your special someone and let the magic happen!** ✨💕🐰
