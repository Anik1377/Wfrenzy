# CSS Utility Classes

## Table 1: CSS Utility Classes

| **Effect**            | **Utility Class**  | **CSS Properties**                                                                                                                                              |
|-----------------------|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **GlassMorphism**     | `.glass`           | ```background: rgba(255, 255, 255, 0.15);``` <br> ```backdrop-filter: blur(10px);``` <br> ```border: 1px solid rgba(255, 255, 255, 0.3);``` <br> ```border-radius: 10px;``` <br> ```box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);``` <br> ```padding: 20px;``` |
| **Box Shadow**        | `.shadow-sm`       | ```box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);```                                                                                   |
|                       | `.shadow-md`       | ```box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1), 0 2px 4px rgba(0, 0, 0, 0.06);```                                                                                   |
|                       | `.shadow-lg`       | ```box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1), 0 4px 6px rgba(0, 0, 0, 0.05);```                                                                                  |
| **Border Radius**     | `.rounded-sm`      | ```border-radius: 4px;```                                                                                                                                       |
|                       | `.rounded-md`      | ```border-radius: 8px;```                                                                                                                                       |
|                       | `.rounded-lg`      | ```border-radius: 16px;```                                                                                                                                      |
| **Text Shadow**       | `.text-shadow-sm`  | ```text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.15);```                                                                                                             |
|                       | `.text-shadow-md`  | ```text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.15);```                                                                                                             |
|                       | `.text-shadow-lg`  | ```text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.15);```                                                                                                             |
| **Text Transformation**| `.uppercase`      | ```text-transform: uppercase;```                                                                                                                                |
|                       | `.lowercase`       | ```text-transform: lowercase;```                                                                                                                                |
|                       | `.capitalize`      | ```text-transform: capitalize;```                                                                                                                               |
| **Opacity**           | `.opacity-0`       | ```opacity: 0;```                                                                                                                                               |
|                       | `.opacity-50`      | ```opacity: 0.5;```                                                                                                                                             |
|                       | `.opacity-100`     | ```opacity: 1;```                                                                                                                                               |
| **Flexbox Layout**    | `.flex`            | ```display: flex;```                                                                                                                                            |
|                       | `.flex-center`     | ```display: flex;``` <br> ```justify-content: center;``` <br> ```align-items: center;```                                                                         |
|                       | `.flex-between`    | ```display: flex;``` <br> ```justify-content: space-between;```                                                                                                 |
| **Text Alignment**    | `.text-left`       | ```text-align: left;```                                                                                                                                         |
|                       | `.text-center`     | ```text-align: center;```                                                                                                                                       |
|                       | `.text-right`      | ```text-align: right;```                                                                                                                                        |
| **Margin**            | `.m-0`             | ```margin: 0;```                                                                                                                                                |
|                       | `.m-1`             | ```margin: 4px;```                                                                                                                                              |
|                       | `.m-2`             | ```margin: 8px;```                                                                                                                                              |
|                       | `.m-3`             | ```margin: 16px;```                                                                                                                                             |
|                       | `.m-4`             | ```margin: 32px;```                                                                                                                                             |
| **Padding**           | `.p-0`             | ```padding: 0;```                                                                                                                                               |
|                       | `.p-1`             | ```padding: 4px;```                                                                                                                                             |
|                       | `.p-2`             | ```padding: 8px;```                                                                                                                                             |
|                       | `.p-3`             | ```padding: 16px;```                                                                                                                                            |
|                       | `.p-4`             | ```padding: 32px;```                                                                                                                                            |
| **Background Color**  | `.bg-primary`      | ```background-color: #007bff;```                                                                                                                                |
|                       | `.bg-secondary`    | ```background-color: #6c757d;```                                                                                                                                |
|                       | `.bg-success`      | ```background-color: #28a745;```                                                                                                                                |
| **Font Size**         | `.text-xs`         | ```font-size: 12px;```                                                                                                                                          |
|                       | `.text-sm`         | ```font-size: 14px;```                                                                                                                                          |
|                       | `.text-md`         | ```font-size: 16px;```                                                                                                                                          |
|                       | `.text-lg`         | ```font-size: 18px;```                                                                                                                                          |
|                       | `.text-xl`         | ```font-size: 20px;```                                                                                                                                          |
| **Font Weight**       | `.font-thin`       | ```font-weight: 100;```                                                                                                                                         |
|                       | `.font-normal`     | ```font-weight: 400;```                                                                                                                                         |
|                       | `.font-bold`       | ```font-weight: 700;```                                                                                                                                         |
| **Hover Effects**     | `.hover-grow`      | ```transition: transform 0.2s;``` <br> ```&:hover { transform: scale(1.05); }```                                                                                 |
|                       | `.hover-shadow`    | ```transition: box-shadow 0.2s;``` <br> ```&:hover { box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15); }```                                                           |
| **Display**           | `.d-none`          | ```display: none;```                                                                                                                                            |
|                       | `.d-inline`        | ```display: inline;```                                                                                                                                          |
|                       | `.d-block`         | ```display: block;```                                                                                                                                           |
|                       | `.d-inline-block`  | ```display: inline-block;```                                                                                                                                    |

## Table 2: Extended CSS Utility Classes

| **Effect**            | **Utility Class**  | **CSS Properties**                                                                                                                                              |
|-----------------------|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Text Color**        | `.text-primary`    | ```color: #007bff;```                                                                                                                                            |
|                       | `.text-secondary`  | ```color: #6c757d;```                                                                                                                                            |
|                       | `.text-success`    | ```color: #28a745;```                                                                                                                                            |
|                       | `.text-danger`     | ```color: #dc3545;```                                                                                                                                            |
|                       | `.text-warning`    | ```color: #ffc107;```                                                                                                                                            |
|                       | `.text-info`       | ```color: #17a2b8;```                                                                                                                                            |
|                       | `.text-light`      | ```color: #f8f9fa;```                                                                                                                                            |
|                       | `.text-dark`       | ```color: #343a40;```                                                                                                                                            |
| **Background Gradient**| `.bg-gradient-primary` | ```background: linear-gradient(90deg, #007bff, #0056b3);```                                                                                                       |
|                       | `.bg-gradient-success` | ```background: linear-gradient(90deg, #28a745, #218838);```                                                                                                       |
|                       | `.bg-gradient-danger` | ```background: linear-gradient(90deg, #dc3545, #c82333);```                                                                                                       |
| **Border Width**      | `.border-0`        | ```border-width: 0;```                                                                                                                                           |
|                       | `.border-1`        | ```border-width: 1px;```                                                                                                                                         |
|                       | `.border-2`        | ```border-width: 2px;```                                                                                                                                         |
|                       | `.border-4`        | ```border-width: 4px;```                                                                                                                                         |
|                       | `.border-8`        | ```border-width: 8px;```                                                                                                                                         |
| **Border Color**      | `.border-primary`  | ```border-color: #007bff;```                                                                                                                                     |
|                       | `.border-secondary`| ```border-color: #6c757d;```                                                                                                                                     |
|                       | `.border-success`  | ```border-color: #28a745;```                                                                                                                                     |
|                       | `.border-danger`   | ```border-color: #dc3545;```                                                                                                                                     |
| **Overflow**          | `.overflow-hidden` | ```overflow: hidden;```                                                                                                                                          |
|                       | `.overflow-auto`   | ```overflow: auto;
