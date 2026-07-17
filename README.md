# My Key Findings
## While exploring the dataset in my notebook, I uncovered a few fascinating orbital patterns:

The Earth-Crossing Limit: There is a strict mathematical boundary where an asteroid's orbit shape and size allow it to cross Earth's path. If its orbit sits below this curve, it can physically never collide with us. I sort of knew of this during my physics degree but it was really cool to see it literally as a hard curve in the chart.

The 140-Meter Rule: NASA only flags an asteroid as potentially hazardous if its diameter is roughly 140 meters or larger. This is why smaller rocks are never labeled as threats on the charts.

The Detection Boom: Our tracking capabilities exploded in the late 1990s and early 2000s when modern automated sky surveys went live.

# The Interactive Dashboard
## The dashboard features four key interactive visualizations:

Orbit Profiles (Scatter Plot): Compares orbit size against orbit shape to show exactly where the hazardous asteroids sit compared to the safe ones.

Threat Levels by Size (Stacked Bar Chart): Groups asteroids by size to show that the vast majority of tracked objects are tiny and harmless.

Diameter Distribution (Box Plot): Uses a log scale to compare physical sizes across the four major asteroid families. It highlights how observational bias makes it much harder for telescopes to spot smaller objects orbiting close to the sun.

Cumulative Discoveries (Area Chart): A stacked area chart showing the exponential growth of our asteroid catalog over time.

# File Structure
index.html: The main page layout hosting the responsive dashboard grid.

chart1.html to chart4.html: The standalone interactive Plotly charts.

Exploration.ipynb: My data cleaning and exploratory analysis pipeline. As well as how I generated the html charts to display in the index.html file and Github Page
