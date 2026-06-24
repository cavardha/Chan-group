CHAN GROUPS REAL ESTATE - FRESH HERO VERSION
===========================================

This version was rebuilt with a fresh hero section for both desktop and mobile.

Main improvements:
- New future-growth hero background image: assets/images/hero-growth.jpg
- Desktop hero uses a clean two-column layout.
- Quick Enquiry form is not squeezed; it has comfortable spacing.
- Mobile hero is compact but readable.
- Mobile menu opens as a 72% width side drawer.
- Mobile gallery works as a swipe slider.
- Sticky bottom buttons: WhatsApp first, Call second.

Open in VS Code:
1. Extract ZIP.
2. Open folder in Visual Studio Code.
3. Right-click index.html.
4. Open with Live Server.

Before publishing, replace sample project text/photos with verified project details.

UPDATE:
- Mobile footer and drawer refined for compact display.
- Drawer now opens as a floating 70% compact panel instead of full-height page.
- Footer links arranged in balanced mobile grid with bottom safe space for sticky buttons.


FINAL COMPACT UI UPDATE
=======================
- Reduced section spacing across desktop and mobile.
- Mobile services now use smaller cards.
- Mobile city and property sections now use horizontal swipe cards to reduce vertical height.
- Quick Enquiry form is compact but still readable.
- Mobile drawer is shorter, lighter and includes Instagram / WhatsApp / Call icons.
- Footer is compressed for mobile with pill links and smaller contact text.


CITY CAROUSEL UPDATE
====================
- City cards auto-slide on mobile every 1 second.
- Added dots below the city cards.
- User can still swipe manually.
- Auto slide pauses briefly during manual touch/swipe.
- City cards were reduced in height for better mobile UI.


CITY SLIDER SPEED + PAGE MOVEMENT FIX
=====================================
- City auto-slide speed changed from 1 second to 3.8 seconds.
- Hero small city strip auto-slide speed changed to 4.2 seconds.
- Replaced scrollIntoView() with horizontal scrollTo(), so the full page will not jump/move during slide change.
- Added carousel stability CSS using overscroll-behavior.


CONTACT + WHATSAPP FORM UPDATE
==============================
- Added Facebook link: https://www.facebook.com/61579498522683
- Added Facebook icon in desktop topbar, mobile drawer, contact section and footer.
- Added 1:1 Property Advice as a paid service.
- Changed Quick Enquiry form to send pre-filled WhatsApp message instead of relying on static form submission.
- Contact section redesigned as compact contact hub to reduce vertical space.
- Services on mobile now use horizontal swipe cards to avoid adding height after adding the paid service.


PROJECT GALLERY UPDATE
======================
You can now add more project images easily.

Folder:
assets/images/projects/

Main list file:
js/gallery-data.js

Steps:
1. Copy your new photos into assets/images/projects/
2. Open js/gallery-data.js
3. Add a new item with the exact file name
4. Save and refresh the website

Important:
A pure static website cannot automatically read all files inside a folder.
So js/gallery-data.js is used as the safe editable image list.


SUPER EASY GALLERY METHOD
=========================

No need to understand js/gallery-data.js.

Use this simple method:
1. Open folder: assets/images/projects/
2. Copy your project photos there.
3. Rename them as:
   project-01.jpg
   project-02.jpg
   project-03.jpg
   project-04.jpg
   project-05.jpg
   project-06.jpg
4. Refresh website.

The website will automatically search from project-01 to project-30.
It supports jpg, jpeg, png and webp.


SOCIAL UPDATE
=============
- Old Facebook link removed.
- New Facebook link added: https://www.facebook.com/changroupsrama
- WhatsApp Channel added: https://whatsapp.com/channel/0029Vb90oEyLI8YOoWBIG93G
- Added Facebook + WhatsApp Channel in:
  * desktop top bar
  * mobile drawer
  * About Rama CH section
  * Contact hub
  * footer socials
- Mobile top bar spacing improved: phone left, social icons right.
- About section UI improved with compact social cards.
