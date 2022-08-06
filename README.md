# Vietnam National Team Data App
Welcome to the GitHub file of my Vietnam National Team data app hosted on Streamlit (you can find the app through the link here: https://darylgouilard-vietnamdataapp-landing-page-iudn3r.streamlitapp.com). This guide will attempt to walk you through the files that are contained in this repo. For the guide on how to use the app, I have made a small section called 'User guide' on the homepage of the app. But I will rewrite an extended version of that section once the app is put to sleep either by Streamlit or by me.

![Capture](https://user-images.githubusercontent.com/63649138/183244933-df54022e-4ea2-4d75-8c86-11d76304e2c2.PNG)

## Folders:
-data: The backbone of the app, which is also the folder that contains all the data of Vietnam's 2022 World Cup Asian Qualifiers and AFF Cup 2020 campaigns (with an addition of Vietnam U23's data from the U23 Asian Cup 2022 - the data is not presented in the app, but it is in the folder since I find it relevant and I could not use it for an article that I planned right after Vietnam U23's elimination from the competition)

-pages: This is the folder that contains the Python codes that run each 'Data page' of the app

## Files:
-MultiPage.py: Originally the code of Prakhar Rathi (https://towardsdatascience.com/creating-multipage-applications-using-streamlit-efficiently-b58a58134030), the code in this file allows the app to run with the multipage functionality.

-config.toml: Set the dark theme as the default for the app (though this is done within the Streamlit Cloud menu, but I am and have used this for another app).

-landing_page.py: The code for the main page of the app, which imports other Python files from the pages folder to create the multipage app.

-requirements.txt: All of the Python libs that I used to create the app
