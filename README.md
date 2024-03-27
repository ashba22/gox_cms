# Welcome to GoX CMS! 🎉

## Demo Version
Check out the [demo version](http://demo.goxcms.xyz/) to see the application in action.
![GoXCMS Home](https://images2.imgbox.com/f5/14/YsFIQzr9_o.png)
![GoXCMS Admin](https://images2.imgbox.com/83/8e/2ITWooA3_o.png)


**Hey there!** Glad you stumbled upon GoX CMS. This project is my playground for experimenting with Go and HTMX to discover the cool interactions they can offer when combined. GoX CMS aims to provide a snappy, secure, and enjoyable content management experience that doesn't feel like a chore.

## Why GoX CMS? 🤔

The motivation behind GoX CMS was to explore the high-performance capabilities of Go and the dynamic, JavaScript-free interactivity offered by HTMX. It serves as a sandbox for experimenting, learning, and breaking things (intentionally!) in a controlled environment. It's also an open invitation for anyone curious about Go and HTMX to dive in and explore.

## What's Cooking? 🍳

As of now, GoX CMS is in its experimental phase - not quite ready for prime time but evolving rapidly. It incorporates:

- **Go**: For robust backend functionality.
- **Fiber**: Offering an Express-like framework but for Go.
- **GORM**: For efficient database management.
- **HTMX**: To refresh pages dynamically without reloading.
- **Bootstrap & BootsWatch**: For stylish UI components.
- **Quill.js**: For sophisticated text editing.
- **Redis**: For fast caching solutions.

## Features

- Blog
- Categories
- Tags
- Custom pages
- Comments
- Simple plugin system
- Many different themes
- Media manager

## Join the Adventure 🚀

Your input is invaluable! Whether you have ideas, bug reports, or just want to say hi, your contributions are greatly appreciated. From tweaking the code to suggesting new features or sharing insights, every bit of engagement helps fuel this project's journey.

## Quick Start 🏁

# Setting Up and Running the Application

Follow these steps to set up and run the application:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ashba22/gox_cms.git
   ```

2. **Navigate into the project directory:**
   ```bash
   cd gox_cms
   ```

3. **Initialize the module:**
   ```bash
   go mod init goxcms
   ```

4. **Download the necessary dependencies:**
   ```bash
   go mod tidy
   ```

5. **Rename the configuration file:**
   ```bash
   mv /config/config-example.yaml /config/config.yaml
   ```
   Update the necessary values in `config.yaml`.

6. **Run the application:**
   ```bash
   go run main
   ```

Now you're ready to use the application!


Explore the code, experiment with changes, and don't hesitate to break things. Your discoveries and creations are what make this project thrive.
