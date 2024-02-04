[Video](https://vimeo.com/user214919587/review/909790916/9510f26f03)


### Step 1: Introduction to Mobile-First Design (1 minute)
- **Objective:** Explain the shift from desktop to mobile web consumption.
- **Key Points:**
  - Highlight the importance of designing for mobile devices first due to increased mobile usage.
  - Emphasize that starting with mobile design allows for focusing on essential features and content.

### Step 2: Examining the Starter Code (1 minute)
- **Objective:** Present the HTML and CSS starter code.
- **Actions:**
  - Show the HTML structure focusing on the `.group` and `.item` classes.
  - Discuss the initial CSS setup, particularly the `flex-direction: column;` for the `.group` class, which is optimal for mobile layouts.

### Step 3: Demonstrating Mobile View (1 minute)
- **Objective:** Show the mobile view using browser tools.
- **Actions:**
  - Use Chrome Developer Tools to inspect the page in mobile view.
  - Highlight how the layout (list of products and services) is optimized for mobile consumption.

### Step 4: Introducing Media Queries (1 minute)
- **Objective:** Explain the concept of media queries for adapting designs to larger screens.
- **Key Points:**
  - Describe media queries as a CSS technique to apply styles based on viewport conditions like width.
  - Introduce a media query that targets viewports wider than 800 pixels.

### Step 5: Implementing Responsive Design for Desktop (2 minutes)
- **Objective:** Adjust the layout for desktop view using media queries.
- **Actions:**
  - Add a media query to the CSS that changes the `.group` class’s `flex-direction` to `row` for screens wider than 800 pixels.
    ```css
    @media all and (min-width: 800px) {
        .group {
            flex-direction: row;
            justify-content: space-around;
        }
    }
    ```
  - Explain how this adjustment utilizes the available space on larger screens without changing the core code, maintaining the mobile-first approach.

### Step 6: Showcasing the Responsive Flexbox Layout (1 minute)
- **Objective:** Demonstrate the responsive layout transition between mobile and desktop views.
- **Actions:**
  - Resize the browser window to show how the layout transitions from a column view on mobile to a row view on desktop screens.
  - Discuss the use of `justify-content: space-around;` to evenly distribute items in a row on larger screens.

### Step 7: Conclusion and Recap (30 seconds)
- **Objective:** Summarize the lesson and emphasize the mobile-first approach.
- **Key Points:**
  - Reinforce the importance of starting with a mobile-optimized design.
  - Highlight the role of media queries in extending designs to accommodate larger screens.

