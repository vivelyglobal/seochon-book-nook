# Seochon Book Nook

A responsive, single-page Seoul neighborhood library concept with live weather and demo umbrella lending.

## Run

Serve the repository root with any static web server, for example:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000. No build or package installation is required.

## Try the umbrella flow

1. Enable **Preview rainy day**.
2. Click **Borrow an Umbrella Now**.
3. Enter your name and a demo ID such as `LIB-123`.
4. Receive a pickup code and a three-day return date.

Registration also supports a name and phone number; demo records are saved only in your browser. Do not enter sensitive personal information.

## Features

- Cream, forest-green, and wood-inspired design with English and Korean touches.
- Seoul date and time in Asia/Seoul.
- Open-Meteo temperature, current conditions, and maximum hourly rain probability over the next 24 hours.
- Lending activates during current precipitation or when rain probability exceeds 50%.
- Rain simulation, labeled weather fallback, membership modal, signup, and pickup confirmation.
- Four curated book previews, illustrative hours and address, and contact link.

## Demo boundaries

This is a fictional library concept. Membership checks are mocked; any well-formed `LIB-` ID passes. Claims do not reserve real umbrellas. There is no server authentication, shared database, inventory management, or real QR code. Hours, contact details, and location copy are illustrative.

External resources: Tailwind CSS CDN, Google Fonts, Unsplash photo, and Open-Meteo API. Network access is required for these resources; the local styling and labeled demo weather keep the page usable if weather cannot load.

See [PROJECT_REPORT.md](PROJECT_REPORT.md) for implementation and validation details.
