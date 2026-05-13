# Privacy Policy for Insightap

**Last updated: May 13, 2026**

## What Insightap Does

Insightap is a browser extension that analyzes web content from X/Twitter, YouTube, and WeChat using AI and displays structured summaries.

## Data Collection

Insightap collects the following data **only when you click the Insightap button**:

- **Website content**: Tweet text, comments, YouTube video transcripts, and WeChat article text from the page you are viewing.

## How Data Is Used

Collected content is sent directly to the AI API endpoint **you configure** (e.g., OpenAI) to generate summaries. Insightap does not operate any intermediate server.

## Data Storage

- **User settings** (API key, model, language, prompt templates) are stored locally in your browser using `chrome.storage.sync`.
- **Cached summaries** are stored in memory only and cleared when the browser is closed.
- No data is stored on any external server controlled by Insightap.

## Data Sharing

Insightap does **not** sell, transfer, or share your data with any third party. The only external communication is between your browser and the API endpoint you configure.

## Third-Party APIs

When you use Insightap, the content you analyze is sent to the API provider you choose (e.g., OpenAI). Please review your API provider's privacy policy for how they handle data.

## Permissions

- **activeTab**: Access the current tab when you click the extension icon.
- **storage**: Save your settings locally.
- **sidePanel**: Display summaries in the browser side panel.
- **Host permissions** (x.com, twitter.com, youtube.com, mp.weixin.qq.com): Inject content script to extract page content for analysis.

## Changes

If this policy changes, the updated version will be posted here with a new date.

## Contact

If you have questions, open an issue on the [GitHub repository](https://github.com/anthropics/insightap-extension).
