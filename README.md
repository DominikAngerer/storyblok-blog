<p align="center">
  <h1 align="center">Storyblok Blog Starter</h1>
</p>
<br><br>


## Try it out!

### 1. Create a Clone of the Storyblok Space

Press the URL below to directly build this Blog
in your own Storyblok space list.

[Press here for your own blog](https://app.storyblok.com/#!/build/41821)

<small>Make sure you're already registered, if not register and press the link again.</small>

### 2. Your Blog is already online!

You can now create new Blog posts. Hurrrray!

### Bonus

#### 1. You want to change the HTML, CSS and JavaScript? Lets start

This repository uses the [Rendering Service](https://www.storyblok.com/docs/Rendering-Service/Introduction) of Storyblok to provide you a quick and easy to use starting point for Snipcart in combination with Storyblok.

```
## Install the CLI
npm install -g storyblok

## setup configuration
storyblok select
```

#### 2. The CLI will ask you questions - answer them like:

1. How should your Project be named - **Your Project Name**    
2. Select the type of your project - **Theme (Storyrenderer/Hosted)**     
3. We got some Themes prepared for you: - **Custom Theme [We will ask you about your Github URL]**      
4. What is your github theme URL? - **https://github.com/dominikangerer/storyblok-snipcart-shop**      
5. What is your space ID? - **YOUR_SPACE_ID** (Can be found on the Space dashboard)     
6. What is your domain? - **YOUR_STORYBLOK_SUBDOMAIN** (Can be found in your Space settings "Location")    
7. What is your theme token? - **YOUR_THEME_TOKEN** (Can be found on the Space dashboard)     

#### 3. Navigate to your project folder in your machine and instead of `gulp` run `npm run dev`.
#### 4. Add `http://localhost:4040/` as new environment in your Storyblok space setting.

The rendering service automatically pushes your new changes to Storyblok using a gulp task in the background. You can have a look at the [Kickstart of Storyblok](https://github.com/storyblok/quickstart) or at the `gulpfile.babel.js` in this repository so you know what will happen next.


## Commands

In the background we're using `gulp` so you can change all the commands below and adopt them to your need.
```
# Start you local dev environment on port 4440
$ npm run dev

# Build static assets (styles, scripts)
$ npm run build

# Sync your current state on the dev environment
$ npm run deploy:dev

# Sync your current state on the live environment
$ npm run deploy:live
```

#### Is there a full documentation about those filters and other possibilities?

Sure! You can find them right here:

- [The Basics of Liquid](https://www.storyblok.com/docs/Rendering-Service/the-basics-of-liquid)
- [The Liquid of Storyblok](https://www.storyblok.com/docs/Rendering-Service/Theme-Documentation)
- [I want my own domain](https://www.storyblok.com/docs/Rendering-Service/Introduction)

<br>
<br>
<p align="center">
<img src="https://a.storyblok.com/f/39898/1c9c224705/storyblok_black.svg" alt="Storyblok Logo">
</p>
