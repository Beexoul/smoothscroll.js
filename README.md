
[![smooth scrolling](smoothscrolling.png)](https://shivarajpaudel.com.np/)



# Smooth Scroll Plugin
[Discord](https://discord.gg/zuefv8YavH)

This repository contains a jQuery plugin for smooth scrolling functionality on webpages.

## Installation

To use this plugin, you need to include jQuery and the smoothscroll.js file in your HTML document. You can include them from a CDN or download the files and host them locally.

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="smoothscroll.js"></script>
```

## Usage

Once you have included jQuery and smoothscroll.js, you can activate smooth scrolling by calling the `.smoothScroll()` method on the desired elements.

```javascript
$(document).ready(function() {
    $('.smoothScroll').smoothScroll();
});
```

You can customize the smooth scrolling behavior by passing options to the `.smoothScroll()` method.

```javascript
$(document).ready(function() {
    $('.smoothScroll').smoothScroll({
        duration: 1000,  // Duration of the scrolling animation in milliseconds
        axis: 'y',       // Scrolling axis ('x', 'y', or 'xy')
        event: 'click',  // Event triggering the smooth scroll ('click' by default)
        stop: true,      // Stop any ongoing smooth scroll animation before starting a new one (true by default)
        target: window,  // Target element to scroll (window by default)
        reset: true      // Reset the scroll position before scrolling (true by default)
    });
});
```

## Contributing

Contributions to this project are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
