# What is "Responsive Web Design"?

- 800px x 600px is a thing of the past!
- Different screens have different resolutions (number of pixels) and densities (number of physical pixels per "screen pixel")
- The technique is to change the layout and serve different images based on the user's screen resolution/density

# What are Media Queries?

- They're like if-statements for your CSS
- The if conditions are based on the Viewport
- (You can also check other things like orientation, screen density, etc.)

# What is a Viewport?

- It's the thing you're looking "through" to see a web page.
- You can scroll it and you can zoom it

# What are breakpoints?

- They are the if-conditions for media queries

# Where should I set my breakpoints?

- approach #1: Goldilocks (small, medium, large)
- appraoch #2: it depends on the design ("wherever the design starts to look crappy")

# What are three ways of handling Responsive Images?

- #1. Background images in CSS (background-size: cover)
- #2. Use srcset to specify different images for different resolutions
- #3. Use <picture> for differently cropped images