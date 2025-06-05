1. At line 19, I created a class (.content) - turned into a container through flexbox (display:flex) and I was trying to align the game's cover images side by side but was failing miserable BECAUSE, even though I made a class container and turned it into a flexbox, the game's cover images come under the <img> tag which I should have been targeting in the first place. As that img tag falls in content class flex-container it becomes a flex child i.e. flex-item which gets aligned horizontally rather than vertically since we changed the main axis of it with flexbox.


