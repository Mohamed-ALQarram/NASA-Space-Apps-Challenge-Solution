# Weather Prediction App

This repository serves as a **central hub** for the Long-Term Weather Prediction Project, which provides long-term probabilities of adverse weather conditions to help users plan outdoor activities months in advance.  
---

## **Project Repositories**

This hub repository links to all the separate components of the project:

- **Backend (ASP.NET Core 8 Web API)**  
  [Link to backend repo](https://github.com/Mohamed-ALQarram/WeatherPrediction)

- **Web Frontend (React)**  
  [Link to web repo](https://github.com/Mohamed-ALQarram/WeatherPredictionUI)

- **Mobile App (Flutter)**  
  [Link to mobile repo] ()

- **Project Documentation (PDF)**  
  [Link to documentation file](https://drive.google.com/file/d/1MQxh7OygXr_wl-axgEimV0d9mpJtXTVt/view?usp=drive_link)

**Live/Running Links (Optional):**  
- [**Web App Demo:**](https://weather-prediction-ui.vercel.app/)  
- **Mobile App Demo / APK Download:** [Link to APK or demo instructions]()

---


## **1. High-Level Project Summary**

We developed a **cross-platform web and mobile app** that provides **long-term probabilities of adverse weather** for any location and date. Using **40 years of NASA Earth observation data** (POWER API, MERRA-2), the app calculates the likelihood of extreme heat, cold, wind, or precipitation. **Google Gemini integration** offers personalized insights, while a **user-friendly interface** allows selection of location/date and exporting results in JSON or CSV format.  

This project enables users to **plan outdoor activities months in advance** with data-driven insights, improving safety and enjoyment by predicting the likelihood of uncomfortable weather conditions.  

---

## **2. Project Details**

The app works by fetching **historical weather data** from NASA POWER API and MERRA-2 datasets for a selected location and date, then performing **statistical analysis** to calculate the probability of extreme weather conditions. The backend, built with **ASP.NET Core 8 Web API**, manages data processing, calculations, and integration with **Google Gemini** for personalized insights.  

**Benefits:**  
- Enables **data-driven decision-making** for outdoor activities.  
- Offers **personalized recommendations** based on historical probabilities.  
- Provides **cross-platform accessibility** through React (web) and Flutter (mobile).  

**Tools & Technologies:**  
- **Backend:** ASP.NET Core 8, C#, Web API  
- **Frontend:** React (Web), Flutter (Mobile)  
- **Data Sources:** NASA POWER API, MERRA-2 datasets  
- **Other:** Google Gemini for AI insights, CSV/JSON export  

**Goals:**  
Deliver **actionable, personalized weather insights** that help users plan outdoor activities safely and effectively months in advance.  

---

## **3. NASA Data**

We used the **NASA POWER API**, which provides access to historical weather and climate datasets, including **MERRA-2**. These datasets include **temperature, precipitation, wind speed, snowfall, snow depth, and cloud cover**.  

Using statistical analysis on these datasets, we calculate probabilities of extreme or uncomfortable weather conditions for any location and date, forming the core functionality of the app. This data inspired our **personalized dashboard** and AI integration via **Google Gemini**.  

---

## **4. Space Agency Partner & Other Data**

**Space Agency Partner Data:**  
- **NASA POWER API** – historical weather and climate data  
- **MERRA-2 datasets** – accessed via NASA POWER API  

**Other Tools & Resources:**  
- **Backend:** ASP.NET Core 8, Web API, C#  
- **Frontend:** React (Web), Flutter (Mobile)  
- **AI Integration:** Google Gemini  
- **Data Export:** CSV/JSON  
- **Open-source Libraries:** Charts, maps, and UI components  

All datasets and resources are **open and publicly available**. No copyrighted materials were used without permission.  

---

## **5. Use of Artificial Intelligence (AI)**

We integrated **Google Gemini** to provide **personalized and simplified recommendations** based on probabilities of adverse weather calculated from NASA historical data. Gemini transforms statistical analysis into **clear, user-friendly insights** without using or modifying any NASA branding.  


## **6. Screenshots & Demo (Optional)**

You can include **images, mockups, or demo screenshots** here to illustrate the UI and features of your app. Store them in a `docs/images/` folder and link like this:

```markdown
![Web App Screenshot](docs/images/web-screenshot.png)
![Mobile App Screenshot](docs/images/mobile-screenshot.png)
