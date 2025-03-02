
# Instagram slideshows by automatically navigating through photos and videos.
![**Preview**](/Preview.png)
**Features:**

1. Toggleable slideshow with a custom delay between slides.

2. Supports both new and old Instagram "Next" button designs.

3. **_Handles videos by waiting for them to play twice before proceeding._**

4. **_Previews all Post in Instagram carousel before Jumping to Next Post._**
 
5. Customizable delay time via an input field.

6. Logs actions and errors for debugging.

**Usages:**

1. Adds a "_Slideshow_" button to the page for enabling/disabling the feature.

2. Allows users to set a _custom delay_ in seconds.

3. Automatically detects and navigates through media in a slideshow.

**Technical Details:**

1. Uses MutationObserver to detect DOM changes and trigger navigation.

2. Implements debouncing to optimize performance.

3. Dynamically creates and styles the toggle button and input field.

**Compatibility:**

1. Designed for Instagram's web interface.

2. Tested with Violentmonkey (chrome,brave,edge), but should work with other userscript managers. 

**Limitations:**

1. Relies on specific DOM structures, which may break if Instagram updates its UI.

2. Assumes the presence of "Next" buttons in the expected locations.
