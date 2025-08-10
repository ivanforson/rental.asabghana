ASAB Car Rental Website
Project Overview
ASAB is a modern, responsive, multi-page static car rental website built with pure HTML, Tailwind CSS, and vanilla JavaScript.
It features:

Home page with hero and search

cars page showing available cars with active booking and details links

Booking page for submitting rental requests

Car details page with images, descriptions, embedded booking form, and car suggestions

Contact and About pages (if included)

All pages share a consistent emerald green gradient theme and modern UI styling.

Pages & Links
Filename	Description	Navigation Links
index.html	Home page	Links to cars, booking, about, contact
cars.html	List of available cars with Book now & Details	Links to booking page & car-details
booking.html	Booking form, accepts optional pre-selected car via URL	Redirects or form submission message
car-details.html	Detailed car info, images, embedded booking form, suggestions	Linked from cars.html “Details”
contact.html	Contact info & form (if provided)	Navigation menu
about.html	About company info	Navigation menu

URL Structure
The site will be hosted at:
https://rentals.asabghana.com/

Example URLs:

Home: https://rentals.asabghana.com/index.html

cars: https://rentals.asabghana.com/cars.html

Booking: https://rentals.asabghana.com/booking.html

Car details: https://rentals.asabghana.com/car-details.html?car=toyota-corolla

Deployment Instructions
Upload all .html files along with any assets (images, if local) to the web root or appropriate folder on the server.

Ensure that:

File names are all lowercase with hyphens (e.g., car-details.html)

URLs and links inside files match these exact filenames.

The hosting environment supports serving static HTML and JS files.

Confirm the Tailwind CSS CDN link is accessible for styling:

html
Copy
Edit
<script src="https://cdn.tailwindcss.com"></script>
If offline or CDN is not allowed, download Tailwind and serve locally or precompile CSS.

Test all pages and navigation links in multiple browsers to ensure smooth flow.

Features to Note
Navigation menus are consistent across pages with hover effects.

cars page has clickable Book now and Details links.

Booking page and Car details page support passing the car model as a URL parameter (?car=car-name) to prefill forms.

Car details page shows multiple images, description, and allows booking on the same page.

Responsive design works on desktops and mobile devices.

Support / Contact
For questions or issues during deployment, please contact:

Project maintainer: [Your Name or Contact Info]

Hosting admin: [Hosting team contact]