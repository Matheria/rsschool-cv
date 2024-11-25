# Sergey Savinkov

## Contacts

### Telegram: [@Ishalldevour](https://t.me/Ishalldevour)

### E-mail: <sensenevercame@gmail.com>

## Skills

- _HTML_
- _CSS (SASS,LESS)_
- _Basic JS_
- _Git_
- _Gulp_
- _BEM_
- _Figma, Photoshop_

## Sample code

```javascript
const filterAdv = (adv, { type, priceRange, rooms, guests, features }) => {
	const [minPrice, maxPrice] = priceRange;
	if (type !== "any" && adv.offer.type !== type) {
		return false;
	}
	if (guests !== "any" && adv.offer.guests !== Number(guests)) {
		return false;
	}
	if (rooms !== "any" && adv.offer.rooms !== Number(rooms)) {
		return false;
	}
	if (adv.offer.price < minPrice || adv.offer.price > maxPrice) {
		return false;
	}
	return !adv.offer.features || !features.every((feature) => adv.offer.features.includes(feature));
};
```

## Education

- **Ural Federal University**
  - _Faculty of Economics_
- **Courses**
  - _[HTML Academy Frontend developer](https://htmlacademy.ru/profession/frontender)_
  - _[WEB-developer 2021](https://www.udemy.com/course/webdeveloper/)_
- **Self-education**
  - _[Modern JavaScript Tutorial](https://learn.javascript.ru/)_
  - _[WEB Standards](https://web-standards.ru/)_
  - _Different YouTube, Telegram channels_

## Languages

- _Russian - native_
- _English - Upper Intermediate_
