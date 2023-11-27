# ma-librairie-react

## About the project

Library create for 14th project in my formation "Application developper - JavaScript React" from OpenClassrooms
This librairie is available on npm and let you have a react modal ready to use. 

## Getting started

1. Install the library :

```
npm i ma-librairie-react --force
```

2. Import in your React project :

```js
import Modal from 'ma-librairie-react';
import 'ma-librairie-react/dist/styles.css';
```

3. Use in your React project :

```jsx
<Modal
  content={<p>Hello world!</p>}
  onClose={() => {
    setModal(false);
  }}
/>
```

## Contact

You can contact me for any problem on my mail : benjaminclairottepro@gmail.com
