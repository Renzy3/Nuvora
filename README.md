# Nuvora

Nuvora is a React + Vite-powered web application that immerses users into a rich **anime-inspired experience**, combining dynamic visuals, multimedia content, and interactive navigation. The platform showcases an anime ecosystem with trailers, promotional content, and a futuristic web interface.

## Demo

Live deployment: [Nuvora on Vercel](https://nuvora-two.vercel.app)

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/0fa59dd3-8372-43ea-bed6-5dab03fa0be3" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e7a79791-a9cc-4528-a0df-81bdbf36b1c7" />


## Features

- **Anime-Centric Design:** Stunning animated visuals and themed UI.
- **Media Integration:** Supports images, MP3, MP4, and other multimedia assets.
- **Responsive Layout:** Works on desktop and mobile devices.
- **Interactive Navigation:** Menu links for Nexus, Vault, Prologue, About, and Contact pages.
- **Trailer Playback:** Users can watch anime trailers directly on the homepage.
- **Public Assets Folder:** Fonts, images, and audio files are served from the `public` directory for easy access.

## Tech Stack

- **Frontend Framework:** [React](https://reactjs.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Deployment:** [Vercel](https://vercel.com/)

## Project Structure

Nuvora/
├─ public/          # Images, audio, fonts, and video assets
├─ src/             # React components and app logic
├─ index.html       # Main HTML file
├─ package.json     # Project dependencies
├─ tailwind.config.js
├─ vite.config.js
└─ README.md


## Setup Instructions

1. Clone the repository:
   git clone https://github.com/Renzy3/Nuvora.git
   cd Nuvora

2. Install dependencies:
3. 
   npm install

4. Run the development server:

   npm run dev


5. Open your browser at `http://localhost:5173` to view the application.

## Deployment

The app is deployed on **Vercel**, which automatically fetches updates from the GitHub repository. Ensure all media files in the `public` folder are added properly, as Vercel does not fetch Git LFS pointers by default.

## Contributing

Contributions are welcome! Please fork the repository, make changes, and submit a pull request. Ensure any new media files are committed directly in the `public` folder, not via Git LFS, to avoid deployment issues.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Also credit to JS Mastery
