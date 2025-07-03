# Plotly.js Mobile Hover Demo

This repository demonstrates the hover behavior of Plotly.js charts on mobile devices,  
focusing on the display and clearing of hover boxes.

## Background

Plotly.js is a powerful JavaScript charting library widely used for interactive graphs.  
On desktop browsers, hover interactions work as expected with mouse events.  
However, on mobile browsers, hover behavior can be inconsistent due to touch events,  
sometimes causing hover boxes to persist (residual hover boxes) even after switching graphs.

This demo provides two HTML files:

- `plotly_hover_example_before_fix.html` — The **unresolved** version showing the residual hover box issue on mobile.  
- `plotly_hover_example_after_fix.html` — The **fixed** version demonstrating a solution to clear hover boxes correctly.

## Usage

1. Open either `plotly_hover_example_before_fix.html` or `plotly_hover_example_after_fix.html` in a mobile browser.  
2. Tap on data points to show a hover box.   
3. Use the buttons to switch between different datasets (e.g., Graph1, Graph2).  
4. Compare how hover boxes behave differently between the two versions on mobile devices.

## Notes

- Both files use Plotly.js version 3.0.1 from CDN.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

