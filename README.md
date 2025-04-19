# Creative Image Slider

This project implements a creative image slider with a sleek design, responsive behavior, and intuitive navigation. It showcases a full-width slider with images and captions, with functionality to navigate between slides using arrows or thumbnails.

## Features
- **Full-Width Image Slider**: Display large images with a smooth transition effect.
- **Captions**: Each image has a caption overlay, providing a description of the image.
- **Navigation Arrows**: Clickable arrows allow users to move forward or backward through the slides.
- **Thumbnail Navigation**: Small image previews below the main slider allow users to jump directly to any slide.
- **Responsive Design**: The slider adjusts gracefully for mobile and tablet views.

## Technologies Used
- **HTML**: Structure of the page and the slider.
- **CSS**: Styling the layout, image sizes, slider behavior, and hover effects.
- **JavaScript**: Implements the logic for slide transitions and thumbnail interaction.

## Files Overview
1. **HTML**: 
   - Contains the markup for the slider container, images, captions, arrows, and thumbnails.
   
2. **CSS**: 
   - Styles the slider and page layout with a gradient background, box shadows, and responsive adjustments for different screen sizes.
   
3. **JavaScript**: 
   - Controls the slider's behavior, including slide changes when arrows or thumbnails are clicked. It dynamically updates the main image position and thumbnail styling.

## How It Works

- The `slider-container` holds the images, each inside a `.slide` div. The images automatically adjust their size to cover the entire container.
- The `changeSlide` function controls navigation via arrow buttons (left and right) that move the slides left or right.
- The `goToSlide` function allows navigation through the thumbnails. Clicking a thumbnail sets the main slide to that corresponding index.
- The slider smoothly transitions between slides using CSS transforms (`translateX`).

### Interactivity
- **Arrows**: Clicking the left or right arrows (`&#10094;` and `&#10095;`) changes the slide.
- **Thumbnails**: Clicking a thumbnail changes the main image to the corresponding one, highlighting the active thumbnail.
  
## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/creative-image-slider.git
