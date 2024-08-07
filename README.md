# AI Article Summarizer

AI Article Summarizer is a web application that uses the OpenAI API to generate summaries of articles. This application is built with React and Redux Toolkit and leverages RapidAPI to fetch and summarize articles.

## Features

- Input URLs of articles to get concise summaries.
- Responsive design for optimal viewing on different devices.
- Simple and intuitive user interface.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Node.js (v14 or higher)
- npm (v6 or higher)
- Git

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/Sukhhh/ai_article_summarizer.git
    cd ai_article_summarizer
    ```

2. **Install Dependencies**

    ```bash
    npm install
    ```

3. **Set Up Environment Variables**

    Create a `.env` file in the root directory and add your RapidAPI key:

    ```plaintext
    VITE_RAPID_API_ARTICLE_KEY=your_rapidapi_key
    ```

## Running the Application

To start the development server, run:

```bash
npm run dev
```

Open your browser and navigate to view the application.

## Usage

1. **Enter the URL of an article** into the input field.
2. **Submit the form** to generate a summary.
3. **View the summarized text** displayed on the page.

## API Integration

This project uses the RapidAPI Article Extractor and Summarizer API. Below is a brief explanation of the API setup.

### RapidAPI Configuration

- **Base URL:** `https://article-extractor-and-summarizer.p.rapidapi.com/`
- **Endpoints:**
  - `GET /summarize`: Summarizes the content of a provided URL.

## Folder Structure

```
ai_article_summarizer
├── public
│   ├── index.html
├── src
│   ├── assets
│   │   └── (images and icons)
│   ├── components
│   │   └── (React components)
│   ├── services
│   │   └── article.js (API service)
│   ├── App.jsx
│   ├── index.jsx
├── .env
├── package.json
├── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
