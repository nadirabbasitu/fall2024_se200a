---
title: Parts
parent: Details
nav_order: 1
description: >-
    Course Outlines
---

# Parts
{:.no_toc}

---

{{ site.parts_description }}:

## Theory

![image](/fall2024_se200a/assets/images/course/theory-breakdown.png)


## Lab

![image](/fall2024_se200a/assets/images/course/lab-breakdown.png)

<script>
        const siteButton = document.getElementById('menu-button');
        const siteNav = document.querySelector('.site-nav');

        let isVisible = false;

        siteButton.addEventListener('click', function(event) {
            event.preventDefault();
            if (isVisible) {
                siteNav.style.display = 'none';
                isVisible = false;
            } else {
                siteNav.style.display = 'block';
                isVisible = true;
            }
        });
    </script>