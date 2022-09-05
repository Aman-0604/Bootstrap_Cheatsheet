# Bootstrap Cheatsheet

### Made by Aman Gupta

1. **This is the style link which you have to include in your index.html below the `title`**\
    `<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">`

2. **This is the javascript link which you have to include in your index.html above the `</body`> tag.**\
    `<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa" crossorigin="anonymous"></script>`

3. **Table for commands**

|      **Commands**      |            **Purpose**           |                            **Comments**                            |
|:----------------------:|:--------------------------------:|:------------------------------------------------------------------:|
| my-3                   | Give a margin of 3 from y-axis   |                                                                    |
| mx-3                   | Give a margin of 3 from x-axis   |                                                                    |
| container              | responsive,fixed-width-container | its max-width changes at each breakpoint.                          |
| container-fluid        | width: 100% at all breakpoints   | a full width container, spanning the entire width of the viewport. |
| d-flex                 | display: flex                    |                                                                    |
| flex-row               | flex-direction : row             |                                                                    |
| justify-content-center | justify-content:center           |                                                                    |
| align-items-center     | align-item: center               |                                                                    |
| mb-2                   | margin-bottom-2                  | {property}{sides}-{size}                                           |
| mb-lg-0                | margin-bottom-large-0            | {property}{sides}-{breakpoint}-{size}                              |
| ml-4                   | margin-left-4                    |                                                                    |
| p-3                    | padding of 3                     |                                                                    |
| mx-auto                | margin-x_axis-auto               | to center the element                                              |
| overflow-auto          | overflow: auto                   | brings a scroll bar if the content starts overflowing the box      |
|                        |                                  |                                                                    |
|                        |                                  |                                                                    |
|                        |                                  |                                                                    |
|                        |                                  |                                                                    |
|                        |                                  |                                                                    |
|                        |                                  |                                                                    |

4. **Link for getting icons for free provided from bootstrap**
    - https://icons.getbootstrap.com/
    - Copy HTML
    - Paste the SVG right into your project's code.
    - example -> `<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-6-circle" viewBox="0 0 16 16">
                <path d="M1 8a7 7 0 1 0 14 0A7 7 0 0 0 1 8Zm15 0A8 8 0 1 1 0 8a8 8 0 0 1 16 0ZM8.21 3.855c1.612 0 2.515.99 2.573 1.899H9.494c-.1-.358-.51-.815-1.312-.815-1.078 0-1.817 1.09-1.805 3.036h.082c.229-.545.855-1.155 1.98-1.155 1.254 0 2.508.88 2.508 2.555 0 1.77-1.218 2.783-2.847 2.783-.932 0-1.84-.328-2.409-1.254-.369-.603-.597-1.459-.597-2.642 0-3.012 1.248-4.407 3.117-4.407Zm-.099 4.008c-.92 0-1.564.65-1.564 1.576 0 1.032.703 1.635 1.558 1.635.868 0 1.553-.533 1.553-1.629 0-1.06-.744-1.582-1.547-1.582Z"/>
                </svg>`
