# Android News Application 
**Submitted by:** Aditya Yadav  

### 📱 Project Overview 
This project is a fully functional Android News Application that fetches and displays live news data from a REST API. It features a Home Screen displaying a list of current headlines and a Details Screen that expands on individual articles. 

### 🛠 Tech Stack & Tools Used 
* **Language:** Kotlin 
* **UI & Layouts:** XML 
* **Architecture Feature:** Data Binding 
* **Network / API:** Retrofit & REST APIs (Connected to a free News API) 
* **Image Loading:** Glide 
* **UI Components:** RecyclerView, CardView, Intent navigation 

### 🚀 Features Implemented 
* **Dynamic Home Screen:** Utilizes a RecyclerView and custom Adapter to smoothly display a list of news articles. 
* **REST API Integration:** Successfully parses complex JSON responses from the live server into Kotlin Data Classes. 
* **Details Navigation:** Clicking any article on the home screen passes the specific article data to a separate Details Screen for full viewing. 
* **Customization & UI Handling:** Hides the empty image box (View.GONE) if an article lacks a thumbnail.
