# Earthly Wisdom change log

Newest first. Each entry says what changed and where: **web** (the Claude version and toybox.shutterchi.com) and/or **app** (the iPhone and iPad app).

## 2026-11-25 (fourth update)

- **Pick it: circles only for tiny countries on your list** (web, app). Only countries you can actually be asked about with your current region and territory settings get a circle, so territories such as Åland or Bermuda keep their real shape unless territories are turned on. A country gets a circle if it's too small to tap even when zoomed all the way in: 22 countries in the whole world, such as Vatican City, Monaco, Malta, Singapore, Bahrain and the small island nations. The circle is a comfortable tap (44 pt across) at full zoom and stays the same patch of the world at every zoom, so it's smaller when you zoom out. Countries no longer switch between circle and real shape.

## 2026-11-25 (third update)

- **Pick it: tiny countries are circles that grow with the map** (web, app). A circle is now a fixed patch of the world, so it grows and shrinks with the map like real land. It's sized to be a comfortable tap (44 pt across) when Italy fills the screen. On the wide globe, the circles are small specks and don't get in the way. The countries that get a circle are the 63 that are too small to tap at that zoom, from Vatican City up to Luxembourg and Cape Verde. When you zoom in far enough that a country's real shape is bigger than a tap, the real shape comes back.

## 2026-11-25 (second update)

- **Pick it: only really tiny countries become dots** (web, app). Dots were limited to countries no bigger than Bahrain. (Replaced by the third update.)
- **Fix: Australia appeared twice** (web, app). Australia's Indian Ocean islands (Christmas and Cocos) share Australia's country code in the map data, so they were counted as a second, tiny "Australia". They're now plain land, and Australia is asked once.

## 2026-11-25

- **Pick it: tiny countries are now tappable** (web, app). Countries too small to tap on screen, such as Vatican City, Monaco, San Marino and many islands, are shown as round dots about a fingertip wide. A tap anywhere on a dot selects it, and the dot lifts and turns green like any other country. When you zoom in far enough that the real shape is big enough to tap, the dot turns back into the shape.
- **Home screen buttons** (app). The two lines of "Name them all" sit closer together, and all three buttons have a little more room inside.

## 2026-11-20

- **New map colours** (web, app). Every country has a colour picked in Figma: mostly soft blues and greens on the big countries, with pinks and purples as accents. The sea and the borders are a darker blue, and Antarctica is grey.
- **Other countries keep their colours** (web, app). When a country is highlighted or selected, the rest of the map no longer fades.

## 2026-11-18

- **New mode: Pick it** (web, app). You get a country's name and find it on the map. Tap a country to select it, then tap it again or press Pick. Getting it on the first try counts as right, one wrong pick counts like a hint, and two or more count as a miss. Skip shows you where it is.
- **The highlighted country rises** (web, app). Once the camera lands, the country to name rises with a green gradient, a soft glow and a shadow, then settles back into place and keeps a drop shadow. In Pick it, the selected country stays raised.
- **Faster taps** (web). Selecting a country responds right away; the map under it is drawn once instead of every frame.
- **Fix** (web). The "Loading border data…" text no longer stays invisibly on top of the map and blocks taps.
- **First version of the native app** (app). The game rebuilt in SwiftUI for iPhone and iPad, with the same modes, hints, regions and progress.

## Before 2026-11-18

- Natural Earth 50m borders, with the camera framing each country's mainland.
- Practice and Name them all modes, hints (names, flag, letters), regions with territories, progress rings, settings and the glass look.
- Hosted on GitHub Pages at toybox.shutterchi.com/earthly-wisdom.
