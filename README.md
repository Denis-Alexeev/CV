# Redirect Page

This repository contains a redirect page that automatically forwards visitors from [denis-alexeev.github.io/CV](https://denis-alexeev.github.io/CV) to the pdf file with my CV.

## How it works
- Uses triple-layer redirect system (meta tag + JavaScript + manual link)
- Works with JavaScript enabled and disabled
- Prevents caching issues
- Properly handles browser history

## Technical details
- Primary: HTML meta refresh tag
- Secondary: JavaScript immediate redirect
- Fallback: Manual link and emergency timeout
- SEO: Proper canonical tags and noindex directive