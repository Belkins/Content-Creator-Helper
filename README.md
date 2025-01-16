# Content Creator Studio – YouTube Only

A single-page HTML tool that helps YouTube creators (for both standard videos and Shorts) generate:

- Bilingual (English + Ukrainian) video descriptions and hashtags  
- Automatic brand detection (e.g., Sephora, L’Oréal, etc.)  
- Seasonal/holiday/event keywords  
- Multiple content category integration (Beauty, Vlog, Fashion, etc.)  
- Competitor “analysis” (purely front-end and approximate)  
- Automatic thumbnail ideas (random suggestions)  
- SEO scoring and feedback on your title and key points  
- Full support for switching the entire UI between English and Ukrainian

## Features

1. **YouTube-Only Focus**  
   - Toggle between “YouTube Video” or “YouTube Shorts.”  
   - Automatically inserts relevant tags like `#Shorts` or `#YouTuber`.

2. **Bilingual Output**  
   - Generates both **English** and **Ukrainian** blocks for your video description and hashtags.

3. **Brand Detection**  
   - A built-in brand database detects mentions like “Sephora,” “Charlotte Tilbury,” etc.  
   - Repeats brand hashtags for added emphasis.

4. **Competitor Insights**  
   - Paste competitor channels or popular titles, and the tool searches for known trending keywords (very simplified logic, no backend required).

5. **Keyword Density Check**  
   - Examines your title and key points to highlight heavily repeated words.

6. **Automatic Thumbnail Suggestions**  
   - Outputs 2–3 random ideas for an eye-catching thumbnail or cover, based on your selected categories and brand references.

7. **LocalStorage Persistence**  
   - All inputs (title, categories, brand references, etc.) persist in the browser. Reloading the page doesn’t clear your work.

## Usage

1. **Clone or Download** this repository.  
2. Open the `index.html` (or whichever filename you use) in your web browser (Chrome, Firefox, Safari, etc.).  
3. You’ll see the main form on the left and a preview + SEO tips on the right.  
4. Select your **language** (English or Ukrainian), fill out the form, and click **Generate Content**.  
5. The “Preview” section will display a bilingual description and hashtags.  
6. Use the “Copy Content” button to copy everything to your clipboard and paste into your YouTube description field.

## Customization

- **Add More Brands**:  
  Open the HTML and look for the `brandDB` array in the script section. Add or remove brands as desired.
  
- **Extend Categories**:  
  In the `hashtagPools` object, add more categories (e.g., “Gaming,” “Cooking,” “Tech Review”) and define your own hashtags in English and Ukrainian.

- **Modify Language Text**:  
  All UI text uses `data-en` and `data-uk` attributes. Update them to refine translations or reword instructions.

- **Seasonal Events**:  
  Expand the `seasonalEvent` `<select>` in the HTML to include other holidays or events if you like.

- **Style & Layout**:  
  The page uses [Tailwind CSS](https://tailwindcss.com/). Adjust the classes or the background gradient to suit your brand identity.

## Notes

- **No Backend**:  
  This project is 100% front-end. No data is sent to any server or API. Everything runs locally in your browser.

- **Disclaimer**:  
  This tool provides **basic** SEO suggestions and brand detection. It doesn’t guarantee search ranking or compliance with YouTube’s policies. Always review your final text before publishing.  

## Contributing

If you have ideas for improvements (more categories, advanced competitor analysis, additional languages, etc.):

1. Fork this repo  
2. Create a new feature branch (`git checkout -b feature/myNewFeature`)  
3. Commit your changes (`git commit -am 'Add awesome feature'`)  
4. Push to the branch (`git push origin feature/myNewFeature`)  
5. Open a Pull Request

## License

[MIT](LICENSE) – You’re free to use, modify, and distribute this code as you wish. If you make meaningful improvements, please consider sharing them back!

---

Enjoy helping creators produce **viral**, **search-friendly** YouTube content with this all-in-one, bilingual Content Creator Studio!
