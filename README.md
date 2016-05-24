![In Progess](https://img.shields.io/badge/In%20Progress--red.svg)

# SBK Checklist
A checklist for contributing in SMACSS, BEM, and KSS in SASS


- [ ] New contributions have correct class names
- [ ] New contributions are organized correctly
- [ ] New contributions are documented

## Class Naming
[BEM](http://getbem.com/)

- [ ] Are your "Blocks" a "Standalone entity that is meaningful on its own"?
 - Use class name selector only IE ".block"
 - No tag names or IDs
 - No depnedency on other blocks/elements
- [ ] Are your Elements organized in relation to Blocks? IE ".block__elem"
 - Use class name selector only
 - No tag name or ids
 - No dependency on other blocks/elements on a page
- [ ] Are your Modifiers correctly related to Elements or Blocks? IE ".block--hidden { }"


## Organized
[SMACSS](https://smacss.com)

- [ ] Is this Base, Layout, Module/Component, or Theme? Is it in the right folder for that?
- [ ] Are states with their appropriate parents?
- [ ] Have you minimized the depth?
- [ ] Have you optimized performance?
  - Use child selectors
  - Avoid tag selectors for common elements
  - Use class names as the right-most selector




## Documentation
[KSS](http://warpspire.com/kss/)
- [ ] Description section
- [ ] Modifiers section (optional)
- [ ] Styleguide section
- [ ] Proprocessor helper documention (optional)
- [ ] Compatibility section


