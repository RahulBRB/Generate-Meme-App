# Meme Generator 😎 

This is a very simple Meme Generator app I made just for fun and to practice. It does simple operations such as fetching random memes from various subreddits using the Meme API. The app allows users to generate memes with a single click and displays the meme's title, image, and author. 

![image](https://github.com/user-attachments/assets/729df651-9bc3-461f-b829-2ca77a849457)

## Features

- Fetches random memes from a list of subreddits
- Displays the meme's title, image, and author
- Includes a "Generate" button to fetch a new meme on demand

## Subreddits Included

- dankmemes
- memes
- wholesomememes
- me_irl
- funny
- comedyheaven
- surrealmemes
- terriblefacebookmemes

## Technologies Used

- HTML
- CSS
- JavaScript
- [Meme API](https://github.com/D3vd/Meme_Api)

## How to Use

1. Clone the repository.
    ```bash
    git clone https://github.com/RahulBRB/Generate-Meme-App.git
    ```
2. Navigate to the project directory.
    ```bash
    cd Generate-Meme-App
    ```
3. Open `index.html` in your preferred browser to use the meme generator.

4. Click on the "Generate" button to load a new meme.

## Code Overview

The main JavaScript functionality is as follows:
- I have an array of subreddit names stored in `reddits` array.
- The `getMeme()` function randomly selects a subreddit from the list, fetches a meme from the Meme API, and updates the DOM with the meme's title, image, and author.
- The "Generate" button triggers the `getMeme()` function when clicked.


## Contribution Guidelines

I welcome all appropriate contributions to enhance the Meme Generator!
### How to Contribute
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.


