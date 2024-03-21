
<p align="center"><img style="height: 200px;" src="https://repository-images.githubusercontent.com/705000958/1b47c336-f552-487c-8455-8c28518fc69c"> </p>


# 🐺 Logger++
Logger++ is a **powerful** *Open Source* Discord *IP Grabber*. <br>
Where **you** can trick your Target into clicking a link for **their** ip.

Logger++ is made possible using [**Vercel**](https://vercel.com/), [**Github**](https://github.com), [**Phython**](https://www.python.org/), & [**Discord**](https://discord.com/).

# 🍎 Table of Contents

* [**Introduction to Logger++**](#-logger)
* [**Table of Contents**](#-table-of-contents)
* [**Documentation**](#-documentation)
    - [**Settings**](#-settings)
        - [**Webhook**](#-webhook)
        - [**Image**](#-image)
        - [**Url**](#-url)
    - [**Creating a Webhook**](#-creating-a-webhook)
    - [**Hosting**](#-hosting)
* [**Info**](#-info)

# 📜 Documentation
Logger++ has settings you can select and this will teach what each one does
+ ## 🔧 Settings
    + ## 📶 Webhook   
        ```python
        "url": "WEBHOOK_URL",
        ```
        > String - Required

        The Discord Webhook Url in which the data will be sent through
    + ## 📷 Image
        ```python
        "enabled": False,
        ```
        > Boolean - Required

        Enables image logger mode.

        **Whats Image logger?**<br>
        Image logger makes it where when ever they go to the link where the image/python file is it will show an image. You can make this Image logger work better with the corrupted image option as they will have to click the link to see the image. Try to trick your target into to middle clicking the image.
        <br><br>

        ```python
        "corrupted-image-preview": False,
        ```
        > Boolean

        Enables corrupted image

        **What does corrupted image do?**<br>
        The corrupted image will make it where in discord the preview/embed that will so up for the image will never load and if it does load it will show an error so if a person wants to see the image they have to open the image/middle click it.
        <br><br>

         ```python
        "url": "IMAGE_URL",
        ```
        > String - Required

        Image that will show up when clicked or if corrupted image is turned off what one will show up in preview/embed.
    + ## 🔗 Url
        ```python
        "enabled": False,
        ```
        > Boolean - Required
        
        Enables url redirect mode

        **Whats Does this do?**
        What Url Redirect mode will do is basically replicate Grabify. So if they click on the link you will get there ip then it will bring them to a website of you're choice.
        <br><br>

        ```python
        "url-redirect": "URL",
        ```
        > String - Required

        What url will the target be redirected to after link is clicked




+ ## 🆕 Creating a  Webhook
    To make a Webhook you will want to follow these steps in [**Discord**](https://discord.com/).

    1. Make a Discord server.
    2. Open your server's settings and go to the integrations tab.
    3. Click the "Create Webhook" button. <img src="https://support.discord.com/hc/article_attachments/1500000463501/Screen_Shot_2020-12-15_at_4.41.53_PM.png">
    4. Now you have a webhook! <img src="https://support.discord.com/hc/article_attachments/360101553853/Screen_Shot_2020-12-15_at_4.51.38_PM.png">

+ ## 🕸 Hosting
    To host this logger we will be using Vercel and Github

    Steps:
    1. Make sure you have a Github and Vercel account
    2. Download this repo using git or githubs visual downloader.
    3. Make a folder called **"api"**.
    4. Drag **"main.py"** and **"requirements.txt"** into the **"api"** folder.
    5. change your phython script to what ever you want to the url to be. (**Ex: youtube or hotdog** )
    6. Make a github repo name it whatever you want your website to be called. (**Ex: linkshortner or imagehosting**)
    7. press upload an existing file.
    8. Now drag the **api** folder into your github repo. then commit changes.
    9. Go to Vercel and make a new project.
    10. Pick your github repo. then press import. then deploy.
    11. it should show you your website url go it it and add **/api/** and whatever you named your phython file **(DONT ADD THE .py)**.
    12. send it to target and boom. **(Also if you go to it yourself you will get your ip first thing)**.

# ℹ Info

I do not condone using this as it breaks Discord's TOS this project was just to test my phython coding skills.
also if you want to make videos using this go ahead just add a link to the description please.

**Please consider giving this repo a star 🌟**

Logo ig:
```
       __                                        
      / /  ___   __ _  __ _  ___ _ __  _     _   
     / /  / _ \ / _` |/ _` |/ _ \ '__|| |_ _| |_ 
    / /__| (_) | (_| | (_| |  __/ | |_   _|_   _|
    \____/\___/ \__, |\__, |\___|_|   |_|   |_|  
                |___/ |___/                              
```
