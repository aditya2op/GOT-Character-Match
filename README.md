# GOT Character Matcher

This app allows users to select a character from the "Game of Thrones" series, and based on the selected character's personality, it finds the character from a preprocessed dataset that has the most similar personality traits. The app then displays images of both the selected character and the recommended character with similar personality traits.

**Summary of the "Game of Thrones Personality Matcher" Project:**

The provided code is a Streamlit web app for a "Game of Thrones Personality Matcher." This app allows users to select a character from the "Game of Thrones" series, and based on the selected character's personality, it finds the character from a preprocessed dataset that has the most similar personality traits. The app then displays images of both the selected character and the recommended character with similar personality traits.

**Features of the "Game of Thrones Personality Matcher" Project:**

1. **Character Selection:**
   - The app provides a dropdown menu that enables users to select a character from the "Game of Thrones" series.

2. **Personality Matching:**
   - After the user selects a character, the app finds the character with the most similar personality traits from a preprocessed dataset.
   - The similarity between characters is calculated using a distance metric, and the character with the smallest distance to the selected character is recommended.

3. **Character Information:**
   - The app fetches character information, including images, from an external API. The API used is "https://thronesapi.com/api/v2/Characters".

4. **Display Images:**
   - The app displays the images of both the selected character and the recommended character with similar personality traits.

**Data Sources:**

- The app uses a preprocessed dataset loaded from the 'data.pkl' file. This dataset likely contains character information, and it seems to have been reduced to 25 characters for the purpose of this app.

- Additional character information and images are fetched from the "https://thronesapi.com/api/v2/Characters" API.

**Libraries Used:**

- The app utilizes several Python libraries for its functionality:
   - Streamlit: For creating the web app interface.
   - Requests: For making HTTP requests to the external API.
   - NumPy: For numerical calculations and array operations.






## Authors

- [@AdityaMishra](https://github.com/aditya2op)

