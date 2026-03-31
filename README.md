# Scrollytelling Project: When Are Homicides Most Common?

## Design Rationale
The goal of my project was to explore whether homicide counts vary by month and whether those patterns differ across cities.

I specifically chose a bar chart because it clearly shows comparisons across discrete time categories (months). The use of Plotly allows for interactivity, such as hover tooltips and a dropdown menu to filter by city. The dropdown filter was chosen over multiple charts because it keeps the interface clean while still allowing exploration. Alternatives considered included multiple small charts or faceting, but those would have made the layout more cluttered in a scrollytelling format.

The scrollytelling layout was designed to guide the user through:
context, dataset introduction, interactive exploration, and interpretation

## Development Process
This project took probably 5 hours in total to complete.

The most time consuming aspects were:
- cleaning and transforming the dataset (dates → months)
- building the Plotly dropdown interaction for city filtering
- setting up the Quarto closeread scrollytelling structure
- debugging deployment issues (Quarto config, docs folder, Vercel)

The visualization was iteratively improved by testing clarity, usability, and responsiveness.

## Key Takeaways

The project demonstrates how interactive visualizations can reveal patterns that are not obvious in static summaries. By allowing users to explore different cities, the visualization supports deeper investigation rather than presenting a single fixed conclusion.
