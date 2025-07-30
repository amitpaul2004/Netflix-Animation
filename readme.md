# 🎬 Netflix Intro Animation (Pure CSS)

This project replicates the iconic Netflix intro animation using only HTML and CSS — **no JavaScript** animations, images, or external libraries involved. The animation mimics the glowing red light brush effect forming a stylized letter, just like the real Netflix intro.

## 🔥 Demo

https://user-images.githubusercontent.com/your-github-id/your-demo.gif  
*(Replace the above with an actual demo gif or link to GitHub Pages if deployed.)*

## 📁 Project Structure

```
.
├── index.html       # Main HTML file with custom <netflixintro> tag
├── style.css        # Core styles and animations
```

## 💡 Features

- Pure CSS animation
- Dynamic support for letters `N`, `E`, `T`, `F`, `L`, `I`, and `X`
- No external dependencies
- Smooth glowing "light brush" and spark effects

## 🚀 How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/netflix-intro-css.git
   cd netflix-intro-css
   ```

2. Open `index.html` in any browser.

3. Change the `letter` attribute in the `<netflixintro>` tag to any of:
   ```
   N, E, T, F, L, I, X
   ```

   Example:

   ```html
   <netflixintro letter="N">
   ```

## 🛠 Customization

- You can adjust the animation speed or colors in `style.css`.
- To animate multiple letters in sequence (like full "NETFLIX"), you'll need to duplicate and time-shift each `<netflixintro>` element.

## 📸 Preview

![Netflix Intro Preview](preview.gif)  
*You can generate a GIF using screen recording software or online tools.*

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
