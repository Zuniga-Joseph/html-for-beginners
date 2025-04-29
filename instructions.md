# 🌐 Build a Basic HTML Website

**Audience**: Complete beginners with little or no experience in web design or coding  
**Goal**: Create a basic website using only HTML and view it in a web browser

---

## 🧰 Part 1: Set Up Your Workspace

1. Turn on your computer and log in.
2. Create a new folder on your desktop.
3. Name the folder `my-website`.
4. Open a plain text editor:
    - **Windows**: Use Notepad
    - **macOS**: Use TextEdit
5. *(macOS only)* Go to `Format > Make Plain Text` in TextEdit.

---

## ✍️ Part 2: Write the HTML Code

6. In the text editor, enter the following code:

    ```html
    <!DOCTYPE html>
    <html>
    <head>
      <title>My First Website</title>
    </head>
    <body>
      <h1>Welcome to My Website</h1>
      <p>This is my first web page using HTML!</p>
    </body>
    </html>
    ```

7. Save the file as `index.html` inside the `my-website` folder.
8. Make sure the file extension is `.html` (not `.txt`).

---

## 🌐 Part 3: View the Web Page

9. Open the `my-website` folder.
10. Double-click `index.html`.
11. Your default browser should open and display your web page.

---

## 🧑‍🎨 Part 4: Customize the Page

12. Open `index.html` in your text editor again.
13. Change the text in the `<title>` tag (this appears in the browser tab).
14. Modify the `<h1>` heading to something personal.
15. Add another paragraph below:

    ```html
    <p>I’m learning how to build websites!</p>
    ```

16. Save the file.
17. Refresh the browser tab to see the updates.

---

## 🖼️ Part 5: Add an Image

18. Save an image (e.g., `dog.jpg`) into the `my-website` folder.
19. Below your last paragraph, add this line:

    ```html
    <img src="dog.jpg" alt="A cute dog" width="300">
    ```

20. Save and refresh to see the image.

---

## 🔗 Part 6: Add a Link

21. Below the image, add this line:

    ```html
    <p>Check out <a href="https://www.wikipedia.org">Wikipedia</a>!</p>
    ```

22. Save and refresh to test the clickable link.

---

## 🎨 Part 7: Add Some Style

23. Inside the `<head>` tag (before `</head>`), insert:

    ```html
    <style>
      body {
        background-color: #f0f0f0;
        font-family: Arial, sans-serif;
        color: #333;
        padding: 20px;
      }

      h1 {
        color: #007acc;
      }
    </style>
    ```

24. Save the file and refresh the browser to see the styled changes.

---

## 🧱 Part 8: Add Another Page

25. Create a new file in the same folder.
26. Add this content:

    ```html
    <!DOCTYPE html>
    <html>
    <head>
      <title>About Me</title>
    </head>
    <body>
      <h1>About Me</h1>
      <p>This is a little more about who I am.</p>
    </body>
    </html>
    ```

27. Save the file as `about.html`.

---

## 🔗 Part 9: Link the Two Pages

28. Open `index.html`.
29. Add this link at the bottom:

    ```html
    <p><a href="about.html">Learn more about me</a></p>
    ```

30. Save and refresh. Test the link to the new page.

---

## ✅ Wrap Up

You’ve successfully created a simple two-page website with HTML. You can now experiment with adding more content, images, or even dive into CSS and JavaScript later!

---
