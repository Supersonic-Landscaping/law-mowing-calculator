
# 📄 Lawn Mowing Service Calculator – Supersonic Landscaping

This **Lawn Mowing Service Calculator** by [Supersonic Landscaping](https://www.supersoniclandscaping.com) is a lightweight, embeddable tool built to help landscaping businesses offer their visitors a quick, estimated cost for lawn mowing services. 

It allows users to input their lawn size and select the terrain type. The calculator dynamically adjusts the estimated mowing time and labor cost based on the difficulty of the terrain.

Designed for **easy embedding** into any landscaping service page, it includes **SEO-friendly schema markup**, **brand attribution**, and a **modern responsive style**.

---

## 🚀 Features
- **Instant Estimates**  
  Calculates estimated mowing time and cost based on user input.

- **Topography Adjustment**  
  Adjusts labor estimates based on terrain difficulty (Flat, Slightly Hilly, Moderately Hilly, Very Hilly, Steep/Complex).

- **Custom Pricing**  
  Accepts a customizable labor rate using `data-labor-price` attribute.

- **SEO Optimized**  
  Includes structured data (`schema.org/WebApplication`) for better indexing and brand association.

- **Plug-and-Play**  
  Lightweight, mobile-friendly, and easy to drop into any webpage.

- **Brand Attribution**  
  Includes a subtle "Tool by Supersonic Landscaping" link for organic branding and backlinking.

---

## 🔧 How to Use

1. **Include the CSS and JavaScript** files on your page.

2. **Add the Widget HTML** where you want the calculator to appear:

```html
<div class="supersonic-lawnmowing-calculator" 
     data-title="Lawn Mowing Estimate" 
     data-labor-price="65.00">
</div>
```

- `data-title` (optional): Custom title for the calculator.
- `data-labor-price` (optional): Custom hourly labor price (default is `$65` if not provided).

3. **That's it!** The widget initializes automatically when the page loads.