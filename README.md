# 👀 Vue Project Advices

## 👻 Styling 
### It's better to use ui libs like [vuetifyj](https://vuetifyjs.com/en/), [vuematerial](https://vuematerial.io/) instead writing custom sass styles 
- a11y, dark/light build-in support 
- fast development
- Customization theme (palette colors, spacing)

## Support SSR
## 🤞 Need tests(jest, testing-library, playwright)
- [testing-library](https://github.com/testing-library/vue-testing-library)
- [jest](https://jestjs.io/)
- e2e tests: [playwright](https://github.com/microsoft/playwright)
## PWA features are not implemented 
- offline mode 
- service worker
## Use Appollo-client instead of vuex and axios combination
