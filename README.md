# Bespoke Brass

This is the storefront for Bespoke Brass, a small handcrafted-brass business. I built it as a freelance client project.

**Live:** https://shantanu2006-football.github.io/bespoke-brass/ (also mirrored on [Vercel](https://bespoke-brass.vercel.app))

## What it does

- A catalogue organised by category, with search and per-product pages
- A checkout that needs no payment gateway: a UPI QR code and pay link generated for the exact order amount, or cash on delivery, with orders confirmed over WhatsApp
- A flat shipping fee on small orders, and address forms that fill in the state from the city
- A layout that works on phones and scales up properly on 1440p and 4K screens

## Stack

Plain static HTML, CSS and JavaScript: `index.html`, `product.html` and `checkout.html`. QR codes are generated in the browser with `qrcode.min.js`. There's no backend, so it's hosted free on GitHub Pages and Vercel.
