🎬 HYBRID MOVIE RECOMMENDATION SYSTEM


This project is a **Movie Recommendation System** that suggests movies based on both **movie content** (genres) and **user preferences**.  
It’s a **hybrid model** that combines:
- **Content-Based Filtering** (using TF-IDF and Cosine Similarity)
- **Collaborative Filtering** (based on user ratings)
- Plus a **Trending Section** showing popular movies loved by many users.

Built and tested completely in **Google Colab** with an interactive **Gradio web app interface**.

 ## What the Project Does
- Recommends movies similar to a selected one (Content-Based)
- Gives personalized movie recommendations for each user (Collaborative)
- Combines both methods to make smarter hybrid suggestions
- Displays trending movies using rating counts and averages
- Runs in Google Colab and launches a clean, interactive Gradio app

## Tech Stack
Python- Programming language
pandas, NumPy - Data handling & analysis
scikit-learn - Machine Learning (TF-IDF, cosine similarity) 
Gradio - Web app interface
MovieLens 100k -  Dataset used for training and testing |

## Dataset Details
The project uses the **[MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/)** which contains:
- 100,000 ratings (scale of 1–5)
- 943 users
- 1,682 movies  
Each user has rated at least 20 movies, making it perfect for building a recommender system.

## Working of the project
1. Upload the `ml-100k.zip` dataset in Colab.  
2. Extract and load the data into pandas.  
3. Use **TF-IDF** to convert movie genres into numerical features.  
4. Compute **cosine similarity** to find related movies.  
5. Create a **user–movie rating matrix** for collaborative filtering.  
6. Combine both results to produce **hybrid recommendations**.  
7. Launch the **Gradio app** and start exploring recommendations interactively.

## How to Run the Project
1. Open the notebook file: `Hybrid_Movie_Recommendation_System.ipynb` in **Google Colab**.  
2. Upload your dataset file: `ml-100k.zip`.  
3. Run all the cells (top to bottom).  
4. A **Gradio link** will appear at the end — click it to open your web app.  
5. Try entering:
   - **User ID:** 1 to 943 (any number in this range)  
   - **Movie Title:** e.g. `Toy Story (1995)`, `Babe (1995)`  

## Example Outputs
| Section                      | Description                                                |
|------------------------------|------------------------------------------------------------|
| **Trending Movies**          | Shows the most popular and highly rated films.             |
| **Content-Based Tab**        | Suggests movies similar in genre to the one you choose.    |
| **Collaborative Tab**        | Recommends movies based on users with similar preferences. |
| **Hybrid Tab**               | Combines both for accurate, personalized results.          |


## Live Demo
🎥 Try the app here → [Click to Launch App](https://8b7ba11ad3a4f50321.gradio.live/)  


## Key Results
• Personalized movie recommendations for any user  
• Similar movie suggestions using genre similarity  
• Trending movie discovery based on ratings  
• Hybrid accuracy with both user & content features  


## Future Improvements
- Add **Matrix Factorization** (SVD) for more accurate collaborative filtering  
- Fetch movie posters and details using the **IMDb API**  
- Deploy permanently on **Hugging Face Spaces** for public access  


## About the Developer
**NANDINI REDDY DAKKATHA**  
 B.Tech in Computer Science & Machine Learning  
 Passionate about Data Science, Machine Learning, and building real-world AI projects  

🔗 [LinkedIn](https://www.linkedin.com/in/nandini-reddy-a870822b7/) | [GitHub](https://github.com/nandinireddy824) | ✉️ nandinireddy.dakkatha87@gmail.com


⭐ *If you liked this project, please give it a star on GitHub — it helps a lot!* ⭐
