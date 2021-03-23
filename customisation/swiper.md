---
description: Slider library
---

# Swiper

[Swiper Documentation](http://swiperjs.com/)

```javascript
	var mySwiper = new Swiper(".swiper_feautures", {
		// Optional parameters
		loop: true,
		cssMode: false,
		mousewheel: false,
		simulateTouch: false,
		centeredSlides: true,
		spaceBetween: 10,
		slidesPerView: 3,
		breakpoints: {
			// when window width is >= 320px
			320: {
				slidesPerView: 1,
			},
			// when window width is >= 480px
			768: {
				slidesPerView: 2,
			},
			1000: {
				slidesPerView: 3,
			},
		},

		// If we need pagination
		pagination: {
			el: ".swiper-pagination",
			clickable: true,
		},

		// Navigation arrows
		navigation: {
			nextEl: ".swiper-button-next",
			prevEl: ".swiper-button-prev",
		},
	});
```

