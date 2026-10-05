# Dynamic Gallery 🖼️

A simple **Dynamic Gallery** webpage created using **HTML5 and CSS3**. The project displays images in a four-column layout using **CSS Flexbox**, with each column containing images arranged in a different order.

## 📌 About the Project

This project demonstrates how HTML and CSS can be used to create a simple image gallery layout.

The webpage contains a **four-column gallery**, where each column displays the same set of images in a different sequence. CSS Flexbox is used to arrange the columns horizontally, while images automatically adjust to the width of their respective containers.

## ✨ Features

* 🖼️ Four-column image gallery
* 🔄 Images displayed in different orders
* 📐 Flexbox-based layout
* 📏 Full-height gallery container
* 🎨 Simple border styling
* 📱 Viewport configuration for different screen sizes
* 💻 Pure HTML and CSS implementation
* 🗂️ Images stored in a separate `images` folder

## 🛠️ Technologies Used

| Technology  | Purpose                                           |
| ----------- | ------------------------------------------------- |
| **HTML5**   | Creating the webpage structure and image elements |
| **CSS3**    | Styling and creating the gallery layout           |
| **Flexbox** | Arranging the gallery columns                     |

## 📂 Project Structure

```text
dynamic-gallery/
│
├── index.html
├── images/
│   ├── 1.png
│   ├── 2.PNG
│   ├── 3.PNG
│   └── 4.PNG
│
└── README.md
```

### 📄 File Description

* **`index.html`** — Contains the HTML structure and internal CSS for the gallery.
* **`images/`** — Contains the images displayed in the gallery.
* **`README.md`** — Contains documentation for the project.

## 🎨 Gallery Layout

The gallery is divided into **four equal-width columns**:

```text
┌──────────┬──────────┬──────────┬──────────┐
│ Image 1  │ Image 3  │ Image 2  │ Image 4  │
│ Image 2  │ Image 1  │ Image 4  │ Image 3  │
│ Image 3  │ Image 2  │ Image 1  │ Image 2  │
│ Image 4  │ Image 4  │ Image 3  │ Image 1  │
└──────────┴──────────┴──────────┴──────────┘
```

Each column contains the same four images but in a different order.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the project folder.
3. Make sure the `images` folder is present in the project directory.
4. Make sure all four image files are correctly named:

   * `1.png`
   * `2.PNG`
   * `3.PNG`
   * `4.PNG`
5. Open **`index.html`** in any modern web browser.
6. Explore the four-column image gallery.

## 🎯 Learning Objectives

This project helps demonstrate:

* Basic HTML document structure
* Adding images using the `<img>` element
* Using relative image paths
* CSS Flexbox
* Percentage-based widths
* Height and width properties
* Borders and box sizing
* Image sizing using CSS
* Organizing project assets into folders

## 💡 Key CSS Concepts

### Flexbox

The gallery container uses:

```css
display: flex;
```

This places the four gallery columns horizontally.

### Equal Columns

Each gallery column uses:

```css
width: 25%;
```

This divides the available horizontal space into four equal sections.

### Responsive Images

The images use:

```css
img {
    width: 100%;
}
```

This allows each image to fill the width of its respective gallery column.

## 🔮 Future Improvements

The project can be enhanced by:

* Adding hover effects to images
* Adding image captions
* Creating a responsive mobile layout
* Adding CSS animations
* Implementing a lightbox image viewer
* Adding JavaScript for dynamic image loading
* Adding filters and categories
* Adding navigation controls

## 👨‍💻 Author

**Anurag Bhati**

GitHub: **[Anurag-Bhati9](https://github.com/Anurag-Bhati9)**

## 📄 License

This project is created for **educational and learning purposes**.

---

⭐ *A beginner-friendly project created to practice HTML images, CSS Flexbox, and gallery layouts.*
