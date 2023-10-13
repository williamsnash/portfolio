# How-To
This is a guide on how to add new pages/ posts/ projects/ galleries to the website

## Pages
1. Create new file in the `_pages` folder with these front matters
    ```YAML
    ---
    layout: page
    title: DISPLAY_NAME
    permalink: /URL
    weight: 15 # higher number = farther right on navbar
    ---
    ```

## Posts
1. Create new file in the `_posts` folder with these front matters 
    ```YAML
    ---
    title: DSIPLAY_NAME
    tags: [ANY_TAGS]
    style: fill
    color: # light or dark
    description: # Short description on the post
    ---
    ```
2. Add material in Markdown format

## Projects
1. Create new file in the `_projects` folder with these front matters
    ```YAML
    ---
    name: DISPLAY_NAME
    tools: [TOOLS_/_SKILLS]
    image: ANY_IMAGE
    description: DESCRIPTION
    external_url: # TODO Add link
    ---
    ```
2. Add material in Markdown format

## Galleries
1. Create a new file in the `_galleries` folder with these front matters
    ```YAML
    ---
    layout: page
    title: Red River Gorge, KY
    url: /gallery/red-river-gorge
    cover_img: /assets/img/red-river-gorge/Stanton,%20KY.jpg
    ---
    ```
2. Create a folder in the `assets/img` folder and add your images to it
3. Done!