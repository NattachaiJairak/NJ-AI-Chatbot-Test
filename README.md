# AI Travel Planner & Guide

This is an AI-powered travel planning application built using Streamlit and Google Generative AI. The app provides recommendations for famous destinations, restaurants, hotels, and transportation options based on user input.

## Features
- **Destinations**: Get information about popular tourist spots.
- **Restaurants**: Discover renowned dining options in the area.
- **Hotels**: Find luxurious and convenient places to stay.
- **Transportation**: Learn about transportation options like public transport, car rental, and walking.
- **Activities**: Get recommendations for activities and experiences in the city.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/my-travel-planner-bot.git
    cd my-travel-planner-bot
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:
    ```bash
    streamlit run streamlit_app.py
    ```

## Usage

1. Open your web browser and navigate to `http://localhost:8501`.
2. Enter your Google Generative AI API Key in the input field provided.
3. Type your travel-related query, such as:
    - "Can you recommend some famous restaurants in London?"
    - "What are the best hotels near Buckingham Palace?"
    - "Tell me some fun activities to do in London."
4. The app will respond with tailored recommendations based on your query.

## Deployment

### Deploying on Streamlit Cloud

1. Go to [Streamlit Cloud](https://streamlit.io/cloud).
2. Create a new app and link it to this GitHub repository.
3. Configure any necessary secrets, such as your Google Generative AI API key.
4. Deploy the app and access it via the link provided by Streamlit Cloud.

### Deploying with Docker

1. Build the Docker image:
    ```bash
    docker build -t my-streamlit-app .
    ```

2. Run the Docker container:
    ```bash
    docker run -p 8501:8501 my-streamlit-app
    ```

3. Open your browser and navigate to `http://localhost:8501`.

## Configuration

To use this app, you will need a Google Generative AI API key. You can obtain this key from the [Google Cloud Platform](https://cloud.google.com/).

1. Once you have your API key, set it in the app when prompted.
2. The app will use this key to generate responses based on user input.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/my-new-feature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/my-new-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to open an issue or reach out to me at [your-email@example.com].
