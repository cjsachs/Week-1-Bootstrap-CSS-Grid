1. CSS Grid vs Flexbox vs Bootstrap
2. CSS Grid Demo
-- wrap starter html code in a container

-- implement grid in css
(grid-template-columnns, gap, px vs percentages vs fr)
NOTE: Always use fr units with CSS Grid for responsiveness

-- More CSS Grid Properties
(grid-template-rows, justify-items, align-items)
NOTE: The default values for justify-items & align-items are STRETCH.

-- Nice template code for grid
(   .container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr))
    }
)

3. Interactive CSS Grid Generator