
**Example 2: YouTube Video with Custom Image/Thumbnail**

```yaml
---
layout: video
title: "Understanding React Hooks: useState and useEffect Explained"
date: 2023-05-01 14:30:00 +0700
tags: [React, Hooks, JavaScript, Frontend]
description: "A clear explanation of the fundamental React Hooks, useState and useEffect, with practical examples for beginners."
image: "/assets/images/react-hooks-thumbnail.png" # Use this image for social sharing AND player background/thumbnail
# Video Specific Fields
video_type: youtube
video_id: "1_IYL9ZMR_Y" # Example YouTube ID
duration: "18:45"
views: "45K"
likes: "2.1K"
timestamps:
  - time: "0:00"
    label: "What are React Hooks?"
  - time: "1:30"
    label: "useState: Managing State"
  - time: "6:15"
    label: "useEffect: Handling Side Effects"
  - time: "11:00"
    label: "Dependencies Array Explained"
  - time: "15:20"
    label: "Cleanup Function in useEffect"
  - time: "17:50"
    label: "Recap"
---

This video breaks down the core concepts behind `useState` and `useEffect`. Learn how to manage component state and handle side effects like data fetching or subscriptions in your functional React components.

Perfect for anyone moving from class components or new to React.

**Example 3: Shorter Tutorial Video**

```yaml
---
layout: video
title: "Quick Tip: Centering a Div with Flexbox"
date: 2023-05-10 09:00:00 +0700
tags: [CSS, Flexbox, Quick Tip]
description: "Learn the fastest and most reliable way to perfectly center an element both horizontally and vertically using CSS Flexbox."
# Video Specific Fields
video_type: youtube
video_id: "dU7QdNl4g4g" # Example YouTube ID
duration: "03:12"
views: "8K"
# Likes omitted
timestamps:
  - time: "0:00"
    label: "The Problem"
  - time: "0:35"
    label: "Flexbox Solution"
  - time: "2:10"
    label: "Code Example"
  - time: "2:50"
    label: "Conclusion"
---

Stop struggling with centering elements! This quick video demonstrates the power of Flexbox for easy vertical and horizontal alignment.

```css
.parent {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh; /* Example */
}
.child {
  /* Your child styles */
}