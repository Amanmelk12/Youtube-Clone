# YouTube Clone

A YouTube clone built with HTML and CSS, featuring a navigation bar, sidebar, responsive search bar design, and responsive video previews.

## Features

- **Navigation Bar**: A top navigation bar for easy access to different sections.
- **Sidebar**: A sidebar for additional navigation options.
- **Responsive Search Bar**: A search bar that adjusts to different screen sizes.
- **Video Previews**: Thumbnails of videos that, when clicked, take you to the actual video on YouTube.

## Project Structure

- **index.html**: The main HTML file containing the structure of the YouTube clone.
- **styles.css**: The CSS file containing styles for the navigation bar, sidebar, search bar, and video previews.
- **Thumbnails/**: A directory containing video thumbnail images.
- **Channel pfp/**: A directory containing channel profile pictures.

## Usage

To view the YouTube clone, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/youtube-clone.git
    ```

2. **Navigate to the project directory**:
    ```sh
    cd youtube-clone
    ```

3. **Open `index.html` in your web browser**:
    ```sh
    open index.html
    ```

## Example Code

Here is an example of the HTML structure for a video preview:

```html
<div class="video-preview">
    <div class="thumbnail-row">
        <a href="https://youtu.be/0nZuYyXET3s?si=D8YKhyyn8c6UAQNd">
            <img class="thumbnail" src="Thumbnails/thumbnail-11.webp">
        </a>
        <div class="video-time">14:20</div>
    </div>
    <div class="video-info-grid">
        <div class="channelpic">
            <img class="profile-pic" src="Channel pfp/channel-11.jpeg">
        </div>
        <div class="video-info">
            <p class="video-title">
                Dubai's Crazy Underwater Train and Other Things #Only in Dubai
            </p>
        </div>
    </div>
</div>
