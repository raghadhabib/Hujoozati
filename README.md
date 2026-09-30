# Hujuzati FrontEnd

Hujuzati is a modern Arabic-language front-end website for booking and managing travel, accommodation, and service-related experiences. It provides users with a simple interface to browse services, explore categories, manage orders, and complete the booking journey in a clean and organized way.

## Project Overview

This project is a static web application built with HTML, CSS, JavaScript, and Bootstrap. It includes pages for:

- Home page
- About us
- FAQ
- Login and account creation
- User profile and wallet
- Favorite and order tracking
- Provider dashboard pages
- Service and hotel details

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Bootstrap
- jQuery
- Slick Carousel
- AOS (Animate On Scroll)
- Font Awesome

## Project Structure

```text
Hujuzati_FrontEnd/
├── index.html
├── about-us.html
├── common.html
├── create_account.html
├── log_in.html
├── profile.html
├── favorite.html
├── wallet.html
├── service_details.html
├── hotel_details.html
├── waiting_order.html
├── waiting_order_details.html
├── on-progress-order.html
├── order_info.html
├── setting.html
├── password.html
├── password2.html
├── password3.html
├── provider/
│   ├── add-new-service.html
│   ├── add-property.html
│   ├── my_service.html
│   ├── profile.html
│   ├── service-profile.html
│   ├── setting-provider.html
│   ├── wallet-provider.html
│   ├── wating-orders.html
│   └── waiting_order_details_provider.html
├── assets/
│   ├── css/
│   ├── img/
│   ├── fonts/
│   ├── js/
│   └── webfonts/
└── README.md
```

## How to Run

Because this is a static front-end project, you can run it in either of these ways:

### Option 1: Open directly

Open the `index.html` file in your browser.

### Option 2: Use a local server

From the project folder, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

- This project does not require a backend to view the UI.
- Assets and styles are stored inside the `assets` folder.
- Some pages are designed for both customer and provider flows.

## License

This project is for educational and demonstration purposes.

## Author

Hujuzati FrontEnd
