![Logo](https://github.com/CodeWizardl/Sentiment-Analysis-App/assets/142290678/351c8fb4-6e71-49f7-bb36-540090e0acbe)

<br>

# Sentiment Analysis App 😊😐😔😡

This sentiment analysis application, built using Streamlit, facilitates sentiment analysis across various data types including text, images, and IMDb movie reviews. Leveraging Natural Language Processing (NLP) techniques, the app extracts sentiments from different forms of data.

## Project Specifications
- **Web Framework**: Streamlit
- **Graphs and Images**: PIL, plotly, cv2
- **Sentiment Analysis Libraries**: textblob, nltk(vader), flair, text2emotion, fer
- **API Request Libraries**: requests, json

## Project Components
1. **Text Analysis**: Applies sentiment analysis on user-provided text.
2. **IMDb Movie Reviews**: Fetches review data from IMDb API based on user-entered movie titles and analyzes the sentiments expressed.
3. **Image Analysis**: Analyzes sentiments from user-uploaded images by detecting faces and providing both individual and overall sentiment analysis.

## Video Demonstrations
1. **Text Analysis**: [Watch Video](https://user-images.githubusercontent.com/54144759/173093720-5b753229-3ea8-428d-a4cb-1384c738382e.mp4)
2. **IMDb Reviews**: [Watch Video](https://user-images.githubusercontent.com/54144759/173201517-909e9bc8-19cc-4667-8a8f-bd19fba75a0d.mp4)
3. **Image Analysis**: [Watch Video](https://user-images.githubusercontent.com/54144759/173202138-a7b0648a-ba13-471d-88d2-c91432958aab.mp4)

## Important Information

### IMDb API
- Documentation: [API Documentation](https://imdb-api.com/api/#Reviews-header)
- **API Key**: Users need to register on the IMDb API website to generate a unique key.
- **API Call Limit**: Limited to 100 calls per day.

### API Specifications
- **Movie API**: `https://imdb-api.com/en/API/SearchMovie/{apiKey}/{movieName}`
- **Review API**: `https://imdb-api.com/en/API/Reviews/{apiKey}/{id}`

## Models Used
- **TextBlob**: Simplifies NLP tasks including sentiment analysis.
- **Flair**: A powerful NLP library for advanced tasks like named entity recognition.
- **Vader**: Specifically designed for social media sentiment analysis.
- **text2emotion**: Recognizes emotions in text across five categories.

## Running the Code
To run the code, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Obtain an API key from IMDb API and replace `{apiKey}` placeholders in the code with your actual API key.
4. Run the Streamlit app by executing `streamlit run app.py` in your terminal.
5. Access the app in your web browser at the specified URL (typically `http://localhost:8501`).

## Future Development Ideas
- Analyzing tweets using the Twitter API.
- Real-time sentiment analysis on video streams.
- Sentiment analysis on audio data.
- Scraping website data for sentiment analysis.

## Thank You!
If you find this project useful, consider giving it a star ⭐️ on the repository.
