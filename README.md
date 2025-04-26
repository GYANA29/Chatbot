# Shopping Assistant Chatbot

An AI-powered shopping assistant chatbot built with Streamlit, TensorFlow, and NLTK.

## Features

- Product search and recommendations
- Price comparison
- Delivery information
- Special offers and discounts
- Payment options
- Interactive chat interface
- Responsive design

## Project Structure

```
shopping_chatbot/
├── app.py              # Main Streamlit application
├── intents.json        # Chatbot intents and responses
├── chatbot_model.h5    # Trained model
├── words.pkl           # Vocabulary
├── classes.pkl         # Intent classes
├── index.html          # Landing page
├── styles.css          # Landing page styles
└── requirements.txt    # Python dependencies
```

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd shopping_chatbot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

1. Start the Streamlit server:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to:
```
http://localhost:8501
```

## Deployment Options

### Option 1: Streamlit Cloud
1. Create a Streamlit Cloud account at https://streamlit.io/cloud
2. Connect your GitHub repository
3. Deploy the application

### Option 2: Heroku
1. Create a Heroku account
2. Install Heroku CLI
3. Create a `Procfile`:
```
web: streamlit run app.py
```
4. Deploy using Heroku CLI:
```bash
heroku create
git push heroku main
```

### Option 3: AWS/GCP
1. Set up a virtual machine
2. Install required dependencies
3. Run the application using a process manager like PM2
4. Set up a reverse proxy (Nginx/Apache)

## Customization

- Modify `intents.json` to add new conversation patterns and responses
- Update the landing page by editing `index.html` and `styles.css`
- Customize the chatbot interface in `app.py`

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 