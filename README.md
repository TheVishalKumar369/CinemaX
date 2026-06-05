# CinemaX 🍿

CinemaX is a modern movie discovery application that allows users to find their favorite movies without hassle. It features a robust search functionality, trending movies tracking, and beautifully presented movie data.

## 🚀 Features

- **Movie Search:** Search for any movie using the TMDB API.
- **Trending Movies:** Discover what's popular right now based on real-time user searches.
- **Responsive Design:** A beautiful, responsive user interface that works seamlessly on desktop and mobile.
- **Debounced Search:** Optimized search that waits for you to stop typing before making API calls.

## 🛠️ Tech Stack

- **Frontend:** React, Vite
- **Backend/Database:** Appwrite (used for tracking trending searches)
- **API:** TMDB (The Movie Database) API for movie data
- **Styling:** CSS / Tailwind CSS

## ⚙️ Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone <your-github-repo-url>
   ```

2. Navigate into the project directory:
   ```bash
   cd cinemaX
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

### Environment Variables

Create a `.env` file in the root of your project and add the following variables. You will need to get API keys from TMDB and set up an Appwrite project:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key_here

VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_TABLE_ID=your_appwrite_collection_or_table_id
```

### Running the App Locally

Start the development server:

```bash
npm run dev
```

Your app will be available at `http://localhost:5173`.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
