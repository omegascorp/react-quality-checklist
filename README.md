# React Quality Checklist

- [ ] Use typed language
- [ ] Prefer TypeScript over Flow, since generated code is much better
- [ ] Use sass
- [ ] Use webpack
- [ ] Use tslint
- [ ] Use jest for unit tests
- [ ] Make shure you have CI with tslint and jest or at least a git prepush hook
- [ ] Use fetch for http calls
- [ ] Create your wrapper service for http calls
- [ ] All http calls should be in actions in case your are using redux
- [ ] Create the wrappers for any third party libraries you use (except common ones like react, redux)
