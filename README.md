#assessment1

assessment1 for FED

Stage 0

To set up I,

1. Created a new private repo on github and invited a collaborator.

2. Downloaded all required files from brightspace and went to my groups respective assessment, which was Andor.

3. Created a new folder called assessment1, and opened up Brackets and made 2 new HTML files, index and story, and put those both in the new folder.

4. Copied and pasted the required images for the website into a new image folder within my assessment1 folder

Stage 1

I started with,

1. Adding a basic skeleton to both of my html files

2. Then added in text from the page-contents.txt file to add a title and footer to both pages and for story.html using h3 for character names and p for text relating to the characters

3. I also added in ul and li elements in preparation for doing the navbar
    
4. I then commit and pushed the current status of the project to github

Stage 2

I then had to add in all images to the files so I,

1. in index.html added the logo for the show at the top within a header, the main splash image inside a main, and the disney plus logo inside a footer
    
2. Repeated the steps for both logos for story.html

3. Added in the character images next to their descriptions

4. Added the resistance image next to the Andor description

5. Addded the three scene images inside a div
    
6. Added suitable "alt" text to every img element

7. I then commit and pushed the current status of the project to github

Stage 3

Since I had previously prepared my required elements I,

1. Insert a elements into my pre-existing li elements on both html pages
    
2. I wrapped the unordered lists inside a nav element
    
3. I then commit and pushed the current status of the project to github

Stage 4

I began by,

1. Basic CSS for index.html such as the background colour, text colour etc.

2. I started to shift my images a little to ensure that they fit better onto the page

3. Once everything except the navbar on index.html was looking okay I created a new css file just for the navbar.

4. I added in my chosen details for nav, ul, li, a, a:hover, (including the hover image) and then adjusted until I felt it accurately matched the provided screenshot

5. I finally added in Google fonts as I needed them, Oswald, Lato and Rationale.

6. Once index.html looked good I started on story.html which was a much bigger task, I added everything into row and column divs following Matt's FED repo.

7. I added orange borders to the images and the top of the headings and adjusted the images and text until I was happy

8. It definitely doesnt look like a 1:1 match but it was the best I could do

9. I then commit and pushed the current status of the project to github

Stage 5

I first,

1. Made my project into a Svelte project.

2. copied my index.html into my +page.svelte

3. created a new folder for my second page

4. created and modified a +page.svelte for story.html

5. Created components for the header, footer, and navbar and added them to +layout, and removed them from my +page files

6. I put my leftover CSS into style tags within the +pages

7. I then commit and pushed the current status of the project to github

Stage 6

I began by,

1. creating a new merch.html and merch.js page and fully designing it within brackets with a form at the bottom

2. to save time I went directly for printing an array looping through json data for my merchandise images using a StarWarsAPI

3. Once the file was working as I wanted it to I then tried to move it into the svelte project the same way I had done for index and story

4. I created a new folder and a new +page for my merch.html design and transferred over any elements or style tags

5. I then copy and pasted my merch.js file and put the contents inside a script tag at the very top of my +page

6. I then had to consult gen-AI as my javascript that had been working fine pre-svelte, no longer worked correctly, the response I got to my query was that it wasn't working because I was using .getelementbyid and it seemed like it was trying to access a html element that hadn't generated yet so was doing nothing, ChatGPT suggested I use onMount and {#each} and it generated me a new version of my script tag to use, so I incorporated that into my +page for my merch page. ChatGPT. (2026). ChatGPT - Svelte DOM Manipulation Issue. [online] Available at: https://chatgpt.com/share/69a9b2b7-baac-800e-ba36-50510bd0c6da [Accessed 5 Mar. 2026].

7. I fixed it up and then commit and pushed the current status of the project to github

Stage 7

Having already included the JSON loop earlier I,

1. Went to https://tailwindcss.com/ and used their search feature to find any and all information I would need for my styles

2. Went through page by page incorporating them into index, story, header.svelte and footer.svelte.

3. Decided not to attempt incorporating Tailwind into merch as I ran into many issues with that page specifically and getting it to work properly and did not want to risk making any mistakes that would be difficult to fix

4. I also could not find anything on https://tailwindcss.com/ for displaying an image on a: hover and I felt it was one of the more important features of the navbar so I decided to also leave that one

5. I commit and pushed the current status of the project to github

EXTRA INFO: I have the signed physical copy of the coverpage to be submit in person as requested 
