Web Element Resources

## Purpose

This repository serves as a centralized location for hosting reusable images and other static web assets used across Team Turner Solutions projects.

Rather than duplicating assets in each project repository, projects can reference files hosted here using GitHub's raw content URLs.

This approach helps maintain consistency across projects and simplifies asset management.

## Using Hosted Images

Use the following URL template to reference an image directly:

```text
https://raw.githubusercontent.com/teamturnersolutions/web-resources/main/[FILENAME]
```

Replace `[FILENAME]` with the name of the image file, including its extension.

### Example

To reference an image named `Avatar.png`:

```text
https://raw.githubusercontent.com/teamturnersolutions/web-resources/main/Avatar.png
```

### HTML Example

```html
<img
  src="https://raw.githubusercontent.com/teamturnersolutions/web-resources/main/[FILENAME]"
  alt="Description of image"
>
```

### CSS Example

```css
.project-image {
    background-image: url(
        "https://raw.githubusercontent.com/teamturnersolutions/web-resources/main/[FILENAME]"
    );
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}
```

## Asset Guidelines

- Use descriptive filenames.
- Keep assets organized and reusable across projects.
- Prefer optimized image formats and reasonable file sizes.
- Use the raw content URL when embedding assets in applications, webpages, or documentation.
- Avoid storing sensitive, confidential, or private information in this repository.

## Repository Structure

Assets may be organized into folders as the collection grows. When referencing an asset in a subfolder, include the folder path in the URL.

```text
https://raw.githubusercontent.com/teamturnersolutions/web-resources/main/[FOLDER]/[FILENAME]
```

---

**Team Turner Solutions**  
Shared web assets for reusable project components and visual resources.
