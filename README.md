# E-Commerce Product Listing Page

A responsive and feature-rich e-commerce frontend built with **React (Vite)**, styled using **React Bootstrap**, and powered by **Fake Store API**.

### Live Demo

🔗 https://e-commerce-web-app-phi-silk.vercel.app/

---

## Project Overview

This application mimics a real-world e-commerce storefront featuring product listings, category filtering, price sorting, pagination, and a mini cart – all built in a day using modern React tools.

### Tech Stack

- **React + Vite** (with JavaScript)
- **React Bootstrap**
- **Axios** for API calls
- **React Icons**  
- **Grid** for layout
- **Fake Store API** (https://fakestoreapi.com/)

---

## Features

## Product Listing
- Fetches all products from the Fake Store API.
- Displays in a responsive grid layout.
- Product Card: Shows **Image**, **Title**, **Price**, **Category**, and **Add to Cart** button.

## Category Filters
- Dynamically fetches categories.
- Filters products based on selected category.

## Sorting
- Sort products by:
  - Price: Low → High / High → Low
  - Title: A–Z / Z–A

## Pagination
- Displays 6–8 products per page.
- Supports Next/Previous or page number navigation.
- Maintains sort/filter state across pages.

## Mini Cart
- Persistent cart state using `useContext`.
- Cart icon with quantity badge.
- Modal cart shows product list, quantity, price, and total.

## Responsive Design
- Fully mobile, tablet, and desktop compatible.
- Responsive Navbar with Cart Icon.

---

---

## Getting Started Locally

Follow these steps to run the project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/abhisehk021/E-Commerce-WebApp
cd e-commerce-web-app
1- npm install
2- npm run dev
3- npm run build




