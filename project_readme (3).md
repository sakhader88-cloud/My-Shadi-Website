# HTML & Web Development Fundamentals

A collection of foundational web development exercises and projects focusing on core HTML5 concepts, structured data tables, forms, nested lists, dynamic media management, and UI cloning using modern styling frameworks like Tailwind CSS.

## 📁 Repository Structure & Modules

Here is a breakdown of the key web files and media assets included in this project:

### 1. `shadi.html` — Matrimony Landing Page Clone

* **Description:** A clone of the Shaadi.com homepage landing section integrated with brand assets and real success story imagery.

* **Key Features:**

  * **Brand Navigation:** Incorporates original SVG branding (`shaadi_logo.svg` and `vip_logo.svg`).

  * **Hero Search Widget:** Interactive multi-field search filter widget (gender, age range, religion, mother tongue) paired with hero banner background visuals (`camp_jul_web_north_mobile_2.jpg.jpeg`).

  * **Success Stories & Gallery:** Displays couple success story assets (`piyas_anindita.jpg`, `shreyashree_sukdev.jpg`, `photo-1583939003579-730e3918a45a.jpg`).

  * **Trust Stats & Features:** Feature grid highlighting guarantees, blue tick verification, and AI matchmaking.

  * **Footer Navigation:** Multi-column layout containing links, privacy disclosures, and copyright details.

### 2. `forms.html` — User Information Input Form

* **Description:** A clean, accessible HTML form demonstrating input handling and field grouping.

* **Key Features:**

  * Enclosed within a `<fieldset>` with a custom `<legend>`.

  * Text inputs, email validation fields, date picker, and radio button options for gender selection.

  * Reset and submit action buttons laid out inside a structured table grid.

### 3. `table.html` & `htmltables.html` — Structured Data & Timetables

* **Description:** In-depth examples showing how to build complex tables in standard HTML.

* **Key Features:**

  * **Employee Directory:** Standard structured table with `<thead>` and `<tbody>`.

  * **Cell Merging:** Advanced exercises using `colspan` and `rowspan` for horizontal and vertical cell merging.

  * **Interactive Schedule/Timetable:** A comprehensive styled weekly work and lecture timetable grid.

### 4. `unorderedclassess.html` — Course Outline & Syllabus Structure

* **Description:** A styled course syllabus layout displaying deep list nesting.

* **Key Features:**

  * Multi-level nested lists using decimal and upper-roman numeral ordering.

  * Modern styling integrated using **Tailwind CSS**.

  * Card container design with subtle shadows and responsive layout.

### 5. `index.html` & `list.html` — Core HTML Elements

* **Description:** Essential practice files for core markup tags.

* **Key Features:**

  * Standard text formatting (`<h1>`–`<h6>`, `<pre>`, `<mark>`, `<i>`, `<del>`).

  * Image embedding with custom attributes.

  * Basic ordered (`<ol>`) and unordered (`<ul>`) list configurations.

---

## 🎨 Asset Catalog

| Asset File Name | Description / Usage |
| :--- | :--- |
| `shaadi_logo.svg` | Main brand header vector logo |
| `vip_logo.svg` | VIP Shaadi elite service vector logo |
| `camp_jul_web_north_mobile_2.jpg.jpeg` | Hero banner photography |
| `piyas_anindita.jpg` | Success story couple photo |
| `shreyashree_sukdev.jpg` | Success story couple photo |
| `photo-1583939003579-730e3918a45a.jpg` | Wedding ceremony feature image |
| `saved_resource.html` | Embedded Cloudflare platform script verification module |

---

## 🚀 How to Run the Files

No build step or server setup is required! You can open any file directly in your browser:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/html-web-development-practice.git
   ```

2. **Navigate into the project directory:**

   ```bash
   cd html-web-development-practice
   ```

3. **Open any file in your default browser:**

   * Double-click on any `.html` file (e.g., `shadi.html` or `forms.html`), or

   * Use a Live Server extension (e.g., VS Code **Live Server**) for auto-refreshing during development.

---

## 🛠️ Technologies Used

* **HTML5:** Semantic markup, tables, forms, SVG embedding, media elements, and nested lists.

* **CSS3:** External stylesheets (`shadi.css`) and inline table styling.

* **Tailwind CSS:** Integrated via CDN for responsive components in `unorderedclassess.html`.