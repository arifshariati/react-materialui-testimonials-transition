# react-materialui-testimonials-transition

React Material UI Testimonials Package provides Easy-to-Use Material UI Card and Paper components generating Testimonial component. Testimonial Package works with independent props i.e image, title, subtitle and testimonial.

### Features

1. Works with independent props i.e image, title, subtitle and testimonial
2. Supports solid and gradient background passed as props
3. Controlable transition (You can turn off with transition={false})
4. Adjustable transition parameters such as transition speed and transition direction

[![NPM](https://img.shields.io/npm/v/react-materialui-testimonials-transition.svg)](https://www.npmjs.com/package/react-materialui-testimonials-transition) [![downloads](https://img.shields.io/npm/dw/react-materialui-testimonials-transition)](https://www.npmjs.com/package/react-materialui-testimonials-transition) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-materialui-testimonials-transition
```

## Usage

```jsx
import React, { Component } from 'react'

import { SlideTestimonial } from 'react-materialui-testimonials-transition'

class Example extends Component {
  render() {
    return (
      <SlideTestimonial
        image='/images/1.jpg'
        alt='Arif Shariati'
        imageRadius='50%'
        title='Arif Shariati'
        subtitle='CEO'
        testimonial={'Awesome React Material UI Testimonial component Package'}
        backgroundGradient={['#FE6B8B', '#FF8E53']}
        backgroundColor='#f9f9f9'
        transition={true}
        direction='left'
        speed={1000}
        shadow={5}
      />
    )
  }
}
```

### SlideTestimonial

```jsx
<SlideTestimonial
  image='/images/1.jpg'
  alt='Arif Shariati'
  imageRadius='50%'
  title='Arif Shariati'
  subtitle='CEO'
  testimonial={'Awesome React Material UI Testimonial component Package'}
  backgroundGradient={['#FE6B8B', '#FF8E53']}
  backgroundColor='#f9f9f9'
  transition={true}
  direction='left'
  speed={1000}
  shadow={5}
/>
```

### FadeTestimonial

```jsx
<FadeTestimonial
  image='/images/1.jpg'
  alt='Arif Shariati'
  imageRadius='50%'
  title='Arif Shariati'
  subtitle='CEO'
  testimonial={'Awesome React Material UI Testimonial component Package'}
  backgroundGradient={['#FE6B8B', '#FF8E53']}
  backgroundColor='#f9f9f9'
  transition={true}
  speed={1000}
  shadow={5}
/>
```

### ZoomTestimonial

```jsx
<ZoomTestimonial
  image='/images/1.jpg'
  alt='Arif Shariati'
  imageRadius='50%'
  title='Arif Shariati'
  subtitle='CEO'
  testimonial={'Awesome React Material UI Testimonial component Package'}
  backgroundGradient={['#FE6B8B', '#FF8E53']}
  backgroundColor='#f9f9f9'
  transition={true}
  speed={1000}
  shadow={5}
/>
```

### GrowTestimonial

```jsx
<GrowTestimonial
  image='/images/1.jpg'
  alt='Arif Shariati'
  imageRadius='50%'
  title='Arif Shariati'
  subtitle='CEO'
  testimonial={'Awesome React Material UI Testimonial component Package'}
  backgroundGradient={['#FE6B8B', '#FF8E53']}
  backgroundColor='#f9f9f9'
  transition={true}
  speed={1000}
  shadow={5}
/>
```

## Package Upate

```bash
npm update
```

## License

MIT © [arifshariati](https://github.com/arifshariati)
