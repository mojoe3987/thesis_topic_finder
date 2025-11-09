# Thesis Topic Finder

This project is designed to help students discover thesis ideas through an interactive HTML interface that acts as a sparring partner. Instead of providing fixed topics, the tool engages users by asking thoughtful, guiding questions to help them reflect, brainstorm, and refine potential thesis subjects. The conversational assistance is powered by OpenRouter's AI.

## Getting Started

1. **Clone the repository**:
   ```sh
   git clone https://github.com/mojoe3987/thesis_topic_finder.git
   ```

2. **Open the HTML file**:
   - Locate the main HTML file (e.g., `index.html`) in the repository.
   - Open it in your web browser.

3. **Set up your API key**:
   - The app requires an API key from [OpenRouter](https://openrouter.ai/).
   - In the HTML file, find the placeholder string `API_KEY_HERE`.
   - Replace `API_KEY_HERE` with your own OpenRouter API key in the code.

   ```html
   const apiKey = "API_KEY_HERE"; // <-- Replace with your OpenRouter API key
   ```

4. **Run and use the app**:
   - Interact with the app to receive guidance and questions that will assist you in generating thesis ideas.

## Features

- AI-powered questioning to guide students toward thesis topics.
- Simple, browser-based interface.
- Helps users reflect and brainstorm, rather than offering generic topics.

## Notes

- An OpenRouter API key is required for the app to function.
- Make sure to keep your API key secure and do not share it publicly.
- If you don’t have an API key yet, visit [OpenRouter](https://openrouter.ai/) to create one.

## License

MIT
