# Teste Frontend - MARVEL API

You must create a single-page application with Vue + Vue Router that consumes Marvel’s API available [HERE](https://developer.marvel.com/docs).
App must have 6 pages:
- WELLCOME PAGE
- CHARACTERS PAGE
- CHARACTER DETAIL PAGE
- COMICS PAGE
- EVENTS PAGE
- CONTACT PAGE

Your application must follow those rules below, we recommend you to check if your app really follow all of them.

## General Rules:
- App must follow and respect [UI STYLE GUIDE](https://www.figma.com/file/b21cB6Ph702fL11DqwoyWP/Teste-Frontend---Bee-Delivery?type=design&node-id=2-2&mode=design&t=3U9mo2tpqc08ckd9-0).
- All data and resources must come from MARVEL'S API in every page reload.
- Must have web version and mobile version.
- Must have components to increase code reusability.
- All UI components must be styled with [Bootstrap 5.3](https://getbootstrap.com).
- Must follow [Bootstrap 5.3](https://getbootstrap.com) grid system.
- Icons must be from [HERE](https://ionic.io/ionicons).

### Rules for MAIN PAGE
- Shows a welcome message to user, "WELCOME TO MARVEL'S DIRECTORY".

### Rules for CHARACTERS PAGE
- Shows a list of characters from marvel’s API.
- Thumbnail and name.
- User can click in any of characters, after that, page will load detailed information of the character at CHARACTER DETAIL PAGE.
- Thumbnail, name, description and it's comics.

###  CHARACTER DETAIL PAGE
- This page is loaded when user clicks in any of characters of characters page.
- Thumbnail, name, description and it's comics.

### Rules for COMICS PAGE
- Shows a list of comics from marvel’s API.
- Thumbnail, title and number of pages.

### Rules for EVENTS PAGE
- Show a list of events from marvel’s API.
- Thumbnail, title, description and date.

### Rules for CONTACT PAGE
- User can provide his name, email, phone and any message he wants.
- The form must validate if email has a valid pattern.
- The form must validate if phone number has a valid pattern. Pattern is (xx) x xxxx-xxxx
- Each input must be validated after user leaves it.
- If input fails on validation, it should be highlighted in red, as FIGMA shows.
- “Send” button must be DISABLED if any validation is failed.
- If all fields in form is validated, when user click at “Send” an alert must be displayed saying “Thank you, we'll reach you as soon as possible”

# BONUS FEATURES
If you delivery any of these features, it will increase your chances.
- Pagination
- Search for characters
- Search for comics

# When you finish
When you finish, you should publish your project in a public reporistory at github.com and send an email to luan@beedelivery.com.br BEFORE the time runs out.

## UI Style Guide
[UI STYLE GUIDE](https://www.figma.com/file/b21cB6Ph702fL11DqwoyWP/Teste-Frontend---Bee-Delivery?type=design&node-id=2-2&mode=design&t=3U9mo2tpqc08ckd9-0).

## Web Prototype
[GO TO FIGMA](https://www.figma.com/proto/IivV2Vq6MJ6a24usioCuUk/Teste-t%C3%A9cnico-Mobile-Bee-Delivery?type=design&node-id=203-2&viewport=1176%2C813%2C0.33&t=qEb3f4U1t5a4suOv-0&scaling=scale-down&starting-point-node-id=212%3A45)

## Mobile Prototype
[GO TO FIGMA](https://www.figma.com/proto/IivV2Vq6MJ6a24usioCuUk/Teste-técnico-Mobile---Bee-Delivery?type=design&node-id=212-45&viewport=1176%2C813%2C0.33&t=qEb3f4U1t5a4suOv-0&scaling=scale-down&starting-point-node-id=212%3A45)

At resources folder, you can find marvel's logo and a favicon.