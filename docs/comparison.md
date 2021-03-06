# React Form Library Comparison

PRs to this page are highly encouraged, _especially_ by the authors of other
form libraries. If you feel that your library is misrepresented (or not included
and you'd like it to be), please correct the mistake.

| Feature                               |                   [🏁 React-Final-Form](https://github.com/final-form/react-final-form#-react-final-form)                    |  [Formik](https://github.com/jaredpalmer/formik)  |  [Redux-Form](https://github.com/erikras/redux-form)  |
| ------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------: | :---------------------------------------------------: |
| Bundle Size                           | [4.1k](https://bundlephobia.com/result?p=final-form) + [2.9k](https://bundlephobia.com/result?p=react-final-form) = **7.0k** | [10.7k](https://bundlephobia.com/result?p=formik) | [27.1k](https://bundlephobia.com/result?p=redux-form) |
| Works without Redux                   |                                                              ✅                                                              |                        ✅                         |                          ❌                           |
| Record-Level Sync Validation          |                                                              ✅                                                              |                        ✅                         |                          ✅                           |
| Record-Level Async Validation         |                                                              ✅                                                              |                        ✅                         |                          ✅                           |
| Field-Level Sync Validation           |                                                              ✅                                                              |                        ✅                         |                          ✅                           |
| Field Level Async Validation          |                                                              ✅                                                              |                        ✅                         |                          ✅                           |
| Field Warnings                        |                                                              ✅                                                              |                        ❌                         |                          ✅                           |
| Calculated Fields                     |                                                              ✅                                                              |                        ❌                         |                          ✅                           |
| Render Prop for Form                  |                                                              ✅                                                              |                        ✅                         |                          ❌                           |
| Render Prop for Field                 |                                                              ✅                                                              |                        ✅                         |                          ❌                           |
| Array Fields                          |                                                   ✅ <sup>[1](#footnote1)                                                    |                        ✅                         |                          ✅                           |
| Avoids unnecessary form rerenders     |                                                              ✅                                                              |           ❌ <sup>[2](#footnote2)</sup>           |                          ✅                           |
| Higher Order Component                |                                                ❌ <sup>[3](#footnote3)</sup>                                                 |                        ✅                         |                          ✅                           |
| Render Prop Component                 |                                                              ✅                                                              |                        ✅                         |                          ❌                           |
| Focus on First Error                  |                          ✅ <sup>[4](https://medium.com/@erikras/focus-on-errors-e569264d33a)</sup>                          |                        ❌                         |                          ❌                           |
| HTML5 Validation                      |                ✅ <sup>[5](https://medium.com/@erikras/react-final-form-html5-validation-7055b867ac51)</sup>                 |                        ❌                         |                          ❌                           |
| Declarative Form Rules                |                      ✅ <sup>[6](https://medium.com/@erikras/declarative-form-rules-c5949ea97366)</sup>                      |                        ❌                         |                          ❌                           |
| Access to form data from outside form |                                                              ❌                                                              |                        ❌                         |                          ✅                           |
| Awesome Optical Illusion Logo         |                                                              ❌                                                              |                        ✅                         |                          ❌                           |

---

<a name="footnote1">1</a>: Via
[`final-form-arrays`](https://github.com/final-form/final-form-arrays) and
[`react-final-form-arrays`](https://github.com/final-form/react-final-form-arrays)
helper libraries.

<a name="footnote2">2</a>: This is not really an issue on all but the most
enormous forms.

<a name="footnote3">3</a>: See [Why no HOC?](faq.md#why-no-hoc)
