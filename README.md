# 🌸 Designing Interactive Visualizations with the Iris Dataset

This project demonstrates how to design interactive data visualizations using the classic **Iris flower dataset**. It explores how interactivity—like filtering, zooming, and hovering—can make visual data exploration more engaging and insightful.

---

## 🎯 Objectives
- Understand the role and impact of interactivity in data visualization.
- Implement various types of interactions (filters, zoom, hover).
- Create interactive plots using **Plotly** and **Bokeh** libraries.

---

## 📊 Visualizations Included

| Type                   | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Static Scatter Plot     | Sepal Length vs Sepal Width using Matplotlib                               |
| Interactive Scatter Plot| Plotly-based dynamic species-wise scatter plot                             |
| Dropdown Filters        | Filter between Setosa, Versicolor, Virginica, or view All                  |
| Hover Tooltips          | Show species and measurement info interactively on hover                   |
| Range Sliders / Zoom    | Plotly range sliders for interactive zoom-in/out                           |
| 3D Scatter Plot         | Explore Sepal and Petal features in 3D                                     |
| Parallel Coordinates    | Multi-dimensional feature comparison                                       |
| Bokeh Dropdown Filter   | Live interactive filtering using Bokeh widgets                             |

---

## 📦 Libraries Used

- `pandas`
- `matplotlib`
- `plotly`
- `bokeh`

---

## 📁 Dataset

The Iris dataset used in this project is a classic multivariate dataset introduced by the British biologist and statistician Ronald Fisher. It’s built-in and accessed using Plotly.

---

## 🚀 How to Run

1. Clone the repository or upload the `.ipynb` notebook to [Google Colab](https://colab.research.google.com/).
2. Install required libraries (if not already available):
   ```bash
   pip install plotly bokeh
