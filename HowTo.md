# How-To
This is a guide on how to add new pages/ posts/ projects/ galleries to the website

## Pages

## Posts

## Projects

## Galleries
1. In the `assets/img` folder, create a new folder for the gallery. This folder name will be used in the gallery page's front matter.
2. Create a new file in the `pages/photos` folder.
    1. Add the following front matter to the file:
        ```
        ---
        layout: page
        title: <Gallery Title>
        permalink: /gallery/<what-you-want-the-url-to-be/
        ---
        ```
    2. Add any details you like to the page.
    3. Finally add
        ```
        {% include elements/image-gallery.html folder="/assets/img/<gallery-folder-name>" %}
        ```
3. In the `pages/photos/galleryIndex.md` file, in the front matter add 
    ```
      - title: <Name>
        image: /portfolio/assets/img/<path-to-cover-img>
        url: /portfolio/gallery/<url-from-2.1>/
    ```