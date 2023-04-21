

# Correkt (public repository)
Correkt is a website and chrome extension that detects misinformation with over 93% accuracy! 

Demo:

<img src="https://github.com/Ramon-W/correkt-public/blob/main/scroll1.gif" data-canonical-src="https://github.com/Ramon-W/correkt-public/blob/main/scroll1.gif" width="400" />

<img src="https://github.com/Ramon-W/correkt-public/blob/main/scroll4.gif" data-canonical-src="https://github.com/Ramon-W/correkt-public/blob/main/scroll4.gif" width="400" />

## Description
Using state-of-the-art NLP techniques, Correkt labels misinformation as soon as it appears on screen, highlighting false statements before generating a short excerpt and list of citations to verify its claims. Powered by a retrieval augmented transformer network that achieves over 93% accuracy on the 12.8K LIAR benchmark dataset, we provide an effective, user-friendly way to banish misinformation from your scrollspace. Our model was trained on over 40k real-world statements scraped from reputable fact-checking websites like Poynter and Politifact, while drawing from a retrieval set of over 21 million passages scraped from Wikipedia, the Washington Post, NYT, and more, providing a level of accuracy, accessibility, and speed that traditional fact-checking just can't match. 

Additionally, through our partnership with AI Art Detector, we will soon integrate our extension with the detection of artificially generated artworks, deepfakes, and, eventually, all types of audio and visual media. For artificially generated artworks, we detect them through two state of the art image classification models, MaxViT and CoAtNet, which fuse vision transformers and CNNs. We used several data augmentation techniques, such as color jittering, drop-path, and random-erase for regularization with over 40k training images scraped and curated from deviantart galleries, subredddits, and more. Our models currently reach an accuracy of 89.8%+ on 10k testing images and can be used to assist communities in determining the source of an artwork submission, human vs AI, as well as determine which of the most popular AI art generative models today created it.	

Popup:

<img src="https://github.com/Ramon-W/correkt-public/blob/main/settings.gif" data-canonical-src="https://github.com/Ramon-W/correkt-public/blob/main/settings.gif" width="300" style='display:inline-block' />

Options:

<img src="https://github.com/Ramon-W/correkt-public/blob/main/options.gif" data-canonical-src="https://github.com/Ramon-W/correkt-public/blob/main/options.gif" width="300" style='display:inline-block' />

## Authors
Alexzendor, Justin, Ryan, Tyler, Henry, Ramon, Jerry, Irena, Kevin, Caitlyn, Kaitlin, Maya, Noah

