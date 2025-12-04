<!-- Banner -->
<p align="center">
  <img src="https://raw.githubusercontent.com/rahulsangolli/spotify-music-recommender-system/refs/heads/main/assets/afdae3cd-0a04-4d07-9d64-de3b92b5633d.png"
       alt="Banner" width="100%" style="max-height:240px; object-fit:cover; display:block; margin:0 auto;">
</p>

<div align="center">

<h1 style="font-size:42px; font-weight:800; margin-bottom:10px;">🎵 Spotify Music Recommender System</h1>

<p style="font-size:18px; max-width:850px; line-height:1.6;">
This project is a simple and clean <b>music recommendation system</b> where I combine both 
<b>content-based</b> and <b>collaborative filtering</b> to build a hybrid recommender.
<br/><br/>
I have designed it in such a way that—even if someone is totally new to machine learning—they can understand 
how songs are recommended based on taste, mood, and listening patterns.
</p>

</div>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">📌 Overview</h2>

<p style="font-size:16px; line-height:1.6; max-width:900px; margin:auto;">
In this project, I built a system that recommends songs in two different ways:
</p>

<ul style="font-size:16px; line-height:1.8; max-width:900px; margin:auto;">
  <li><b>Content-Based Recommendations</b> — Finds songs similar in vibe, genre, mood, tempo, etc.</li>
  <li><b>Collaborative Filtering</b> — Recommends songs based on what other users with similar taste enjoyed.</li>
</ul>

<p style="font-size:16px; max-width:900px; margin:auto; line-height:1.6;">
I also integrated both approaches into a <b>hybrid recommendation engine</b>, which makes the results more personalized.  
<br/><br/>
For my demonstrations, I used <b>Taylor Swift songs</b> as examples—not because the model is restricted to her, 
but because the dataset I used had a good number of her songs.  
This allows me to clearly show how similarity, tempo, and mood influence recommendations.
</p>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">🧠 Tech Stack</h2>

<ul style="font-size:16px; line-height:1.8; max-width:900px; margin:auto;">
  <li><b>Languages:</b> Python</li>
  <li><b>Libraries:</b> Pandas, NumPy, Scikit-Learn</li>
  <li><b>Algorithms:</b> TF-IDF, Cosine Similarity, Collaborative Filtering</li>
  <li><b>App Framework:</b> Streamlit</li>
  <li><b>Versioning & Pipelines:</b> DVC</li>
</ul>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">⭐ Key Features</h2>

<ul style="font-size:16px; line-height:1.8; max-width:900px; margin:auto;">
  <li><b>Content-Based Recommendations</b> — Recommends songs with similar mood, genre, and acoustic features.</li>
  <li><b>Collaborative Filtering</b> — Uses user history to find songs liked by similar listeners.</li>
  <li><b>Hybrid Mode</b> — Combines both methods to generate more accurate suggestions.</li>
  <li><b>Clean UI</b> — Simple interface built using Streamlit.</li>
  <li><b>Clear Explanations</b> — Designed for easy understanding, even for beginners.</li>
</ul>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">🖼️ Application Screenshots</h2>

<br/>

<h3 style="font-size:22px; font-weight:700;">1️⃣ Main Interface – Simple & User Friendly</h3>
<p style="font-size:16px; line-height:1.6;">
This is the home screen of the app. I intentionally kept the UI simple so that anyone visiting it for the first time can immediately understand what to do.  
There are no distractions—just three clear options:
<br/><br/>
<b>Content-Based</b> | <b>Collaborative</b> | <b>Hybrid Recommendations</b>
<br/><br/>
This clean interface helps users start exploring recommendations instantly.
</p>
<img src="https://raw.githubusercontent.com/rahulsangolli/spotify-music-recommender-system/refs/heads/main/assets/Screenshot%202025-12-04%20at%206.58.03%E2%80%AFPM.jpeg" width="800px"/>

<br/><br/>

<h3 style="font-size:22px; font-weight:700;">2️⃣ Content-Based Recommendation – Taylor Swift Example</h3>
<p style="font-size:16px; line-height:1.6;">
Here, I selected the song <b>"Love Story"</b> by Taylor Swift.  
The system takes the selected song and finds other songs that have:
<ul>
  <li>similar lyrics (after converting them into mathematical features),</li>
  <li>similar mood or genre,</li>
  <li>similar acoustic features like tempo, loudness, and energy level.</li>
</ul>
This helps users understand how “song similarity” actually works in music platforms.
</p>
<img src="https://raw.githubusercontent.com/rahulsangolli/spotify-music-recommender-system/refs/heads/main/assets/Screenshot%202025-12-04%20at%207.01.39%E2%80%AFPM.jpeg" width="800px"/>

<br/><br/>

<h3 style="font-size:22px; font-weight:700;">3️⃣ Content-Based Results – Output Songs</h3>
<p style="font-size:16px; line-height:1.6;">
After entering “Love Story,” the system returns a set of songs that feel similar.  
These recommendations are displayed in a clean list format so users can quickly glance through the suggested tracks.
<br/><br/>
This screen helps users see how content-based filtering works in a real-life scenario.
</p>
<img src="https://raw.githubusercontent.com/rahulsangolli/spotify-music-recommender-system/refs/heads/main/assets/Screenshot%202025-12-04%20at%207.02.01%E2%80%AFPM.jpeg" width="800px"/>

<br/><br/>

<h3 style="font-size:22px; font-weight:700;">4️⃣ Collaborative Filtering – User Listening Example</h3>
<p style="font-size:16px; line-height:1.6;">
Collaborative filtering works differently compared to the content approach.
<br/><br/>
This method does NOT look at song lyrics or mood.
<br/><br/>
Instead, it studies:
<ul>
  <li>what users listened to,</li>
  <li>which users have similar taste,</li>
  <li>what similar users enjoyed recently.</li>
</ul>
If another listener has a listening pattern similar to yours, the system recommends songs they liked—even if they are from different artists or genres.
</p>
<img src="https://raw.githubusercontent.com/rahulsangolli/spotify-music-recommender-system/refs/heads/main/assets/Screenshot%202025-12-04%20at%207.03.06%E2%80%AFPM.jpeg" width="800px"/>

<br/><br/>

<h3 style="font-size:22px; font-weight:700;">5️⃣ Hybrid Recommendation – The Best of Both Worlds</h3>
<p style="font-size:16px; line-height:1.6;">
The hybrid method mixes both approaches:
<br/><br/>
<b>Content + User Behavior = Highly personalized and accurate suggestions</b>
<br/><br/>
This method helps when:
<ul>
  <li>a user is new (cold-start problem),</li>
  <li>song metadata is limited,</li>
  <li>album-based similarities are not enough,</li>
  <li>we want deeper personalization.</li>
</ul>

This final view shows the combined suggestions—not just songs similar to "Love Story," but also songs people with similar taste enjoyed.
</p>

<img src="https://raw.githubusercontent.com/rahulsangolli/spotify-music-recommender-system/refs/heads/main/assets/Screenshot%202025-12-04%20at%207.03.56%E2%80%AFPM.jpeg" width="800px"/>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">🧩 How the System Works</h2>

<p style="font-size:16px; line-height:1.6; max-width:900px; margin:auto;">
Here’s a simple explanation of how the entire system works—without using complex machine-learning terms:
</p>

<ol style="font-size:16px; line-height:1.8; max-width:900px; margin:auto;">

<li><b>Collecting Music Data</b>  
We start with a dataset containing songs, their artists, moods, tempo, and sometimes even lyrics.  
This data helps the system learn what makes each song unique.
</li>

<li><b>Cleaning the Data</b>  
Some songs may have missing information, repeated names, or formatting issues.  
So the first job is to clean everything so that the model understands the data correctly.
</li>

<li><b>Content-Based Learning</b>  
Here, the system tries to understand the “soul” of each song—its features like genre, mood, and acoustic profile.  
Once a user picks a song, the system finds similar ones.
</li>

<li><b>Collaborative Filtering Learning</b>  
This part behaves like:
<br/>
<i>“If people who like Song A also like Song B, maybe you’ll like Song B too.”</i>
<br/>
It studies real user listening behavior.
</li>

<li><b>Hybrid Model</b>  
Finally, both systems talk to each other and combine their suggestions.  
This produces well-balanced recommendations.
</li>

<li><b>Streamlit App</b>  
Everything is presented inside a clean Streamlit app where users can select a song and instantly see recommendations.
</li>

</ol>

<hr/>

<h2 style="font-size:28px; font-weight:700;" align="center">📈 Results</h2>

<ul style="font-size:16px; line-height:1.8; max-width:900px; margin:auto;">
  <li>High-quality recommendations using both content and user patterns.</li>
  <li>Easy-to-understand interface for demonstrating how recommendation systems work.</li>
  <li>Hybrid model performs better than using only one technique.</li>
</ul>

<hr/>

<div align="center">

<h2 style="font-size:32px; font-weight:800;">👨‍💻 Author</h2>

<strong style="font-size:24px;">Rahul Sangolli</strong><br>
<em style="font-size:16px;">Data Science & Machine Learning Practitioner</em>

<p style="font-size:16px;">
<a><b>🌐 LinkedIn (Coming Soon)</b></a> &nbsp;|&nbsp;
<a href="mailto:your-email"><b>✉️ Email</b></a>
</p>

</div>
