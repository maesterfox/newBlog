

# Next.js, Tailwind CSS, TypeScript & Sanity Blog

Welcome to the repository for the Next.js blog designed and developed by David Fox. This blog showcases a modern web development stack using Next.js, Tailwind CSS, TypeScript, and Sanity CMS. It's built to deliver a powerful and seamless blogging experience, featuring a responsive design and efficient content management.

## Features

- **Modern Stack**: Built using Next.js, Tailwind CSS, TypeScript, and Sanity CMS.
- **Responsive Design**: The blog is fully responsive, ensuring it works on all devices.
- **Rich Text Editor**: Integrated with Sanity's Portable Text for rich text editing.
- **SEO Friendly**: Utilizes Next.js's powerful SEO capabilities.
- **Light and Dark Mode**: Supported by `next-themes` for user-preferred theme settings.

## Live Demo

Check out the live version of the blog [here](https://newblog-inia.onrender.com/).

## Repository

The code is available on GitHub: [maesterfox/newBlog](https://github.com/maesterfox/newBlog)

## Installation

To get this project running on your local machine, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/maesterfox/newBlog.git
    cd newBlog
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up Sanity**:
    - Create a Sanity project at [Sanity.io](https://www.sanity.io/)
    - Configure the schemas as defined in the `schema.ts` file.
    - Replace the dataset configuration in the Sanity studio with your own.

4. **Configure Environment Variables**:
    - Create a `.env.local` file in the root directory.
    - Add the following environment variables:
        ```plaintext
        SANITY_PROJECT_ID=your_sanity_project_id
        SANITY_DATASET=your_dataset_name
        ```

5. **Start the development server**:
    ```bash
    npm run dev
    ```

    Access the blog at [http://localhost:3000](http://localhost:3000).

## Building and Deployment

To build the project for production, run:
```bash
npm run build
```
Followed by:
```bash
npm start
```

## Contributing

Contributions are always welcome! Please read the contribution guidelines first.

## About the Author

- **David Fox**
  - **Portfolio**: [davidfoxdev.co.uk](https://www.davidfoxdev.co.uk)
  - **LinkedIn**: [linkedin.com/in/davidfoxtechcode](https://www.linkedin.com/in/davidfoxtechcode)

Feel free to connect with me on LinkedIn or check out my portfolio for more projects and professional information.