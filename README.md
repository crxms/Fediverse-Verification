# Fediverse Verification Repository

This repository is used to host an HTML file for verifying my profiles on various Fediverse platforms, including Mastodon, Friendica, PixelFed, and Lemmy (via Lemm.ee), using `rel="me"` links.

## Purpose

The verification process involves adding `<link rel="me">` tags in an HTML file hosted here. These links allow platforms like Mastodon, Friendica, PixelFed, and Lemmy to confirm that my profiles are associated with this repository or domain. 

## How It Works

1. **Verification HTML File**:
   - The repository contains an HTML file with multiple `<link rel="me">` tags pointing to my profiles on supported Fediverse platforms.

2. **`rel="me"` Links**:
   - The `rel="me"` attribute is a standard way to declare relationships between webpages, allowing Fediverse servers to crawl and verify links between my profiles and this repository.

3. **Example HTML**:
   Here’s an example of the content in the verification file:
   ```html
   <link rel="me" href="https://mastodon.example/@yourusername">
   <link rel="me" href="https://friendica.example/profile/yourusername">
   <link rel="me" href="https://pixelfed.example/@yourusername">
   <link rel="me" href="https://lemm.ee/u/yourusername">
