

# Correkt (public repository)
Correkt is a website and chrome extension that detects misinformation with over 93% accuracy! 

Demo:

<img src="https://github.com/Ramon-W/correkt-public/blob/main/scroll1.gif" data-canonical-src="https://github.com/Ramon-W/correkt-public/blob/main/scroll1.gif" width="400" />

<img src="https://github.com/Ramon-W/correkt-public/blob/main/scroll4.gif" data-canonical-src="https://github.com/Ramon-W/correkt-public/blob/main/scroll4.gif" width="400" />

Popup:

<img src="https://github.com/Ramon-W/correkt-public/blob/main/settings.gif" data-canonical-src="https://github.com/Ramon-W/correkt-public/blob/main/settings.gif" width="300" style='display:inline-block' />

Options:

<img src="https://github.com/Ramon-W/correkt-public/blob/main/options.gif" data-canonical-src="https://github.com/Ramon-W/correkt-public/blob/main/options.gif" width="300" style='display:inline-block' />

## Description
Using state-of-the-art NLP techniques, Correkt labels misinformation as soon as it appears on screen, highlighting false statements before generating a short excerpt and list of citations to verify its claims. Powered by a retrieval augmented transformer network that achieves over 93% accuracy on the 12.8K LIAR benchmark dataset, we provide an effective, user-friendly way to banish misinformation from your scrollspace. Our model was trained on over 43k real-world statements scraped from reputable fact-checking websites like Poynter and Politifact, while drawing from a retrieval set of over 21 million passages scraped from Wikipedia, the Washington Post, NYT, and more, providing a level of accuracy, accessibility, and speed that traditional fact-checking just can't match.

Additionally, through our partnership with AI Art Detector, we're adding deepfake detection to our suite of features! This will give our extension the ability to detect artificially generated artwork, images, and, eventually, all types of audio and visual media. AI Art Detector works using two state of the art image classification models which fuse vision transformers and CNNs. We used several data augmentation techniques, such as color jittering, drop-path, and random-erase for regularization with over 40k training images scraped and curated from deviantart galleries, subredddits, and more. This image classification model currently reaches an accuracy of 89.8%+ on 10k testing images and can detect the source of an artwork submission, whether it's human vs AI, as well as determine which of the most popular generative models today created it.

Demo:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/HtHq403H4xU/maxresdefault.jpg)](https://youtu.be/HtHq403H4xU)

## Authors
Alexzendor, Justin, Ryan, Tyler, Henry, Ramon, Jerry, Irena, Kevin, Caitlyn, Kaitlin, Maya, Noah

