
Built by https://www.blackbox.ai

---

```markdown
# Sistem Penomoran Surat - Kecamatan Masama

## Project Overview
Sistem Penomoran Surat is a web-based application designed for managing incoming and outgoing letters at Kecamatan Masama, Kabupaten Banggai. With a user-friendly interface, it allows authorized personnel to authenticate, view, manage, and search letters efficiently. 

## Installation
To set up this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd sistem-penomoran-surat
   ```

2. **Open the project in a web browser:**
   Simply open the `index.html` file in your web browser. Ensure that you open other HTML files (`login.html`, `dashboard.html`, etc.) for navigating through the application.

## Usage
1. Upon opening the application, you will be redirected to the **Login** page.
2. Enter the default password `Masama2023!` to gain access.
3. Once logged in, you will reach the **Dashboard**, where you can view counts of incoming and outgoing letters.
4. You can manage letters by navigating to the **Incoming** and **Outgoing** sections to add, edit, or delete letters.
5. You can utilize the **Search** feature to find specific letters by number, subject, or sender/recipient.

## Features
- User Authentication
- Dashboard Overview of Letters
- Management of Incoming Letters
- Management of Outgoing Letters
- Search Functionality for Letter Lookup
- Responsive Design using Tailwind CSS

## Dependencies
The project relies on the following external libraries:
- [Tailwind CSS](https://tailwindcss.com) for styling.
- [Font Awesome](https://fontawesome.com/) for icons.

These libraries are included via CDN links in the HTML files.

## Project Structure
```
├── index.html          # Entry point for the application
├── login.html          # Login page for user authentication
├── dashboard.html      # Dashboard displaying letter statistics
├── incoming.html       # Management page for incoming letters
├── outgoing.html       # Management page for outgoing letters
├── search.html         # Search page for finding letters
├── config.js           # Configuration settings for the application
```

### Notes
- The application data is currently stored in the browser's `localStorage`, allowing you to test the functionality without a backend server.
- Make sure you have a modern web browser to fully utilize the features provided.

## Author
Created by: Pedry Lengeh
```