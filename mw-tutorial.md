# Interactive Plotting Components (mw)

This blog features several custom interactive components (prefixed with `mw`) for visualizing Gaussian processes and related concepts. Here’s a quick guide to each:

---

## 1. mwColorScale
**File:** `src/components/ColorScale.html`  
Displays a color legend for heatmaps or density plots.

**Usage:**  
```html
<mwColorScale min={0} max={1} colorMap="viridis" />
```

---

## 2. mwCovMat2x2
**File:** `src/components/CovMat2x2.html`  
Visualizes a 2x2 covariance matrix, showing uncertainty or correlation.

**Usage:**  
```html
<mwCovMat2x2 matrix={[[1, 0.5], [0.5, 1]]} />
```

---

## 3. mwDimensionSwapFigure
**File:** `src/components/DimensionSwapFigure.html`  
Lets you swap axes or dimensions interactively to explore data.

**Usage:**  
```html
<mwDimensionSwapFigure data={yourData} />
```

---

## 4. mwGaussianContours
**File:** `src/components/GaussianContours.html`  
Plots contour lines of a 2D Gaussian distribution.

**Usage:**  
```html
<mwGaussianContours mean={[0, 0]} cov={[[1, 0], [0, 1]]} />
```

---

## 5. mwInteractiveGaussian
**File:** `src/components/InteractiveGaussian.html`  
Interactively adjust the mean and covariance of a Gaussian and see the plot update in real time.

**Usage:**  
```html
<mwInteractiveGaussian />
```

---

## 6. mwKernelCombinations & mwKernelCombinationsStatic
**Files:**  
- `src/components/KernelCombinations.html`  
- `src/components/KernelCombinationsStatic.html`  
Visualize and combine different kernel functions for Gaussian processes.

**Usage:**  
```html
<mwKernelCombinations />
<mwKernelCombinationsStatic />
```

---

## 7. mwMarginalizationConditioning
**File:** `src/components/MarginalizationConditioning.html`  
Demonstrates marginalization and conditioning in multivariate Gaussians.

**Usage:**  
```html
<mwMarginalizationConditioning />
```

---

## 8. Prior & Posterior Visualizations
**Files:**  
- `src/components/PriorFigure.html`  
- `src/components/PriorSample.html`  
- `src/components/PriorSampling.html`  
- `src/components/Posterior.html`  
- `src/components/PosteriorFigure.html`  
Show samples from the prior and posterior distributions of a Gaussian process.

**Usage:**  
```html
<mwPriorFigure />
<mwPriorSample />
<mwPriorSampling />
<mwPosterior />
<mwPosteriorFigure />
```

---

## 9. mwTeaser
**File:** `src/components/Teaser.html`  
A summary or introductory visualization for the blog post.

**Usage:**  
```html
<mwTeaser />
```

---

## 10. Utility Functions
**Files:**  
- `src/components/util/context.js`  
- `src/components/util/limit.js`  
Helper functions for context management and value limiting, used internally by the components.

---

**How to Use:**  
Import any component in your Svelte file and add it to your markup as shown above. Customize the props as needed for your visualization.

---

Feel free to copy and paste this section into your blog, adjusting the explanations or usage examples as needed!
