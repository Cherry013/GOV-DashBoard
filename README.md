# GOV-DashBoard
Error in vercel:

[15:44:16.181] Cloning github.com/Cherry013/GOV-DashBoard (Branch: main, Commit: 1d9ef5c)
[15:44:16.721] Cloning completed: 538.984ms
[15:44:17.562] Looking up build cache...
[15:44:17.798] Build Cache not found
[15:44:17.848] Running "vercel build"
[15:44:18.493] Vercel CLI 28.4.4
[15:44:18.853] Installing dependencies...
[15:44:29.259] npm WARN deprecated source-map-resolve@0.6.0: See https://github.com/lydell/source-map-resolve#deprecated
[15:44:30.138] npm WARN deprecated querystring@0.2.0: The querystring API is considered Legacy. new code should use the URLSearchParams API instead.
[15:44:32.928] npm WARN deprecated flatten@1.0.3: flatten is deprecated in favor of utility frameworks such as lodash.
[15:44:45.051] npm WARN deprecated @angular/http@6.1.10: Package no longer supported. Use @angular/common instead, see https://angular.io/guide/deprecations#angularhttp
[15:44:55.744] npm WARN deprecated core-js@2.6.12: core-js@<3.23.3 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Some versions have web compatibility issues. Please, upgrade your dependencies to the actual version of core-js.
[15:44:56.473] npm WARN deprecated core-js@3.19.0: core-js@<3.23.3 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Some versions have web compatibility issues. Please, upgrade your dependencies to the actual version of core-js.
[15:45:03.833] 
[15:45:03.833] added 1131 packages in 45s
[15:45:03.833] 
[15:45:03.833] 99 packages are looking for funding
[15:45:03.834]   run `npm fund` for details
[15:45:07.625] - Generating browser application bundles (phase: setup)...
[15:45:15.371] ✔ Browser application bundle generation complete.
[15:45:15.378] ✔ Browser application bundle generation complete.
[15:45:15.384] 
[15:45:15.384] Warning: /vercel/path0/PalnaduDashboard/src/environments/environment.prod.ts is part of the TypeScript compilation but it's unused.
[15:45:15.384] Add only entry points to the 'files' or 'include' properties in your tsconfig.
[15:45:15.385] 
[15:45:15.385] 
[15:45:15.385] 
[15:45:15.385] ./node_modules/css-loader/dist/runtime/api.js - Error: Module build failed (from ./node_modules/@ngtools/webpack/src/ivy/index.js):
[15:45:15.385] Transform failed with 1 error:
[15:45:15.385] error: Invalid version: "15.2-15.3"
[15:45:15.385] 
[15:45:15.386] ./node_modules/css-loader/dist/runtime/noSourceMaps.js - Error: Module build failed (from ./node_modules/@ngtools/webpack/src/ivy/index.js):
[15:45:15.386] error: Invalid version: "15.2-15.3"
[15:45:15.386] 
[15:45:15.386] ./src/main.ts - Error: Module build failed (from ./node_modules/@ngtools/webpack/src/ivy/index.js):
[15:45:15.386] Transform failed with 1 error:
[15:45:15.386] error: Invalid version: "15.2-15.3"
[15:45:15.387] 
[15:45:15.387] ./src/polyfills.ts - Error: Module build failed (from ./node_modules/@ngtools/webpack/src/ivy/index.js):
[15:45:15.387] Transform failed with 1 error:
[15:45:15.387] error: Invalid version: "15.2-15.3"
[15:45:15.387] 
[15:45:15.387] ./src/styles.css - Error: Module build failed (from ./node_modules/mini-css-extract-plugin/dist/loader.js):
[15:45:15.388] HookWebpackError: Module build failed (from ./node_modules/@ngtools/webpack/src/ivy/index.js):
[15:45:15.388] Transform failed with 1 error:
[15:45:15.388] error: Invalid version: "15.2-15.3"
[15:45:15.389]     at tryRunOrWebpackError (/vercel/path0/PalnaduDashboard/node_modules/webpack/lib/HookWebpackError.js:88:9)
[15:45:15.389]     at __webpack_require_module__ (/vercel/path0/PalnaduDashboard/node_modules/webpack/lib/Compilation.js:4979:12)
[15:45:15.389]     at __webpack_require__ (/vercel/path0/PalnaduDashboard/node_modules/webpack/lib/Compilation.js:4936:18)
[15:45:15.389]     at Module.<anonymous> (/vercel/path0/PalnaduDashboard/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[2].rules[0].oneOf[1].use[1]!/vercel/path0/PalnaduDashboard/node_modules/postcss-loader/dist/cjs.js??ruleSet[1].rules[2].rules[0].oneOf[1].use[2]!/vercel/path0/PalnaduDashboard/src/styles.css:5:111)
[15:45:15.390]     at /vercel/path0/PalnaduDashboard/node_modules/webpack/lib/javascript/JavascriptModulesPlugin.js:432:11
[15:45:15.390]     at Hook.eval [as call] (eval at create (/vercel/path0/PalnaduDashboard/node_modules/tapable/lib/HookCodeFactory.js:19:10), <anonymous>:7:1)
[15:45:15.390]     at /vercel/path0/PalnaduDashboard/node_modules/webpack/lib/Compilation.js:4981:39
[15:45:15.390]     at tryRunOrWebpackError (/vercel/path0/PalnaduDashboard/node_modules/webpack/lib/HookWebpackError.js:83:7)
[15:45:15.390]     at __webpack_require_module__ (/vercel/path0/PalnaduDashboard/node_modules/webpack/lib/Compilation.js:4979:12)
[15:45:15.391] -- inner error --
[15:45:15.391] Error: Module build failed (from ./node_modules/@ngtools/webpack/src/ivy/index.js):
[15:45:15.391] Transform failed with 1 error:
[15:45:15.391] error: Invalid version: "15.2-15.3"
[15:45:15.392]     at Object.<anonymous> (/vercel/path0/PalnaduDashboard/node_modules/@angular-devkit/build-angular/src/babel/webpack-loader.js??ruleSet[1].rules[1].use[0]!/vercel/path0/PalnaduDashboard/node_modules/@ngtools/webpack/src/ivy/index.js!/vercel/path0/PalnaduDashboard/node_modules/css-loader/dist/runtime/noSourceMaps.js:1:7)
[15:45:15.392]     at /vercel/path0/PalnaduDashboard/node_modules/webpack/lib/javascript/JavascriptModulesPlugin.js:432:11
[15:45:15.392]     at Hook.eval [as call] (eval at create (/vercel/path0/PalnaduDashboard/node_modules/tapable/lib/HookCodeFactory.js:19:10), <anonymous>:7:1)
[15:45:15.392]     at /vercel/path0/PalnaduDashboard/node_modules/webpack/lib/Compilation.js:4981:39
[15:45:15.392]     at tryRunOrWebpackError (/vercel/path0/PalnaduDashboard/node_modules/webpack/lib/HookWebpackError.js:83:7)
[15:45:15.392]     at __webpack_require_module__ (/vercel/path0/PalnaduDashboard/node_modules/webpack/lib/Compilation.js:4979:12)
[15:45:15.393]     at __webpack_require__ (/vercel/path0/PalnaduDashboard/node_modules/webpack/lib/Compilation.js:4936:18)
[15:45:15.393]     at Module.<anonymous> (/vercel/path0/PalnaduDashboard/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[2].rules[0].oneOf[1].use[1]!/vercel/path0/PalnaduDashboard/node_modules/postcss-loader/dist/cjs.js??ruleSet[1].rules[2].rules[0].oneOf[1].use[2]!/vercel/path0/PalnaduDashboard/src/styles.css:5:111)
[15:45:15.393]     at /vercel/path0/PalnaduDashboard/node_modules/webpack/lib/javascript/JavascriptModulesPlugin.js:432:11
[15:45:15.394]     at Hook.eval [as call] (eval at create (/vercel/path0/PalnaduDashboard/node_modules/tapable/lib/HookCodeFactory.js:19:10), <anonymous>:7:1)
[15:45:15.395] 
[15:45:15.396] Generated code for /vercel/path0/PalnaduDashboard/node_modules/@angular-devkit/build-angular/src/babel/webpack-loader.js??ruleSet[1].rules[1].use[0]!/vercel/path0/PalnaduDashboard/node_modules/@ngtools/webpack/src/ivy/index.js!/vercel/path0/PalnaduDashboard/node_modules/css-loader/dist/runtime/noSourceMaps.js
[15:45:15.396] 1 | throw new Error("Module build failed (from ./node_modules/@ngtools/webpack/src/ivy/index.js):\nTransform failed with 1 error:\nerror: Invalid version: \"15.2-15.3\"");
[15:45:15.396] 
[15:45:15.396] Generated code for /vercel/path0/PalnaduDashboard/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[2].rules[0].oneOf[1].use[1]!/vercel/path0/PalnaduDashboard/node_modules/postcss-loader/dist/cjs.js??ruleSet[1].rules[2].rules[0].oneOf[1].use[2]!/vercel/path0/PalnaduDashboard/src/styles.css
[15:45:15.397]  1 | __webpack_require__.r(__webpack_exports__);
[15:45:15.397]  2 | /* harmony export */ __webpack_require__.d(__webpack_exports__, {
[15:45:15.397]  3 | /* harmony export */   "default": () => (__WEBPACK_DEFAULT_EXPORT__)
[15:45:15.397]  4 | /* harmony export */ });
[15:45:15.398]  5 | /* harmony import */ var _node_modules_css_loader_dist_runtime_noSourceMaps_js__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__("/vercel/path0/PalnaduDashboard/node_modules/@angular-devkit/build-angular/src/babel/webpack-loader.js??ruleSet[1].rules[1].use[0]!/vercel/path0/PalnaduDashboard/node_modules/@ngtools/webpack/src/ivy/index.js!/vercel/path0/PalnaduDashboard/node_modules/css-loader/dist/runtime/noSourceMaps.js");
[15:45:15.399]  6 | /* harmony import */ var _node_modules_css_loader_dist_runtime_noSourceMaps_js__WEBPACK_IMPORTED_MODULE_0___default = /*#__PURE__*/__webpack_require__.n(_node_modules_css_loader_dist_runtime_noSourceMaps_js__WEBPACK_IMPORTED_MODULE_0__);
[15:45:15.399]  7 | /* harmony import */ var _node_modules_css_loader_dist_runtime_api_js__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__("/vercel/path0/PalnaduDashboard/node_modules/@angular-devkit/build-angular/src/babel/webpack-loader.js??ruleSet[1].rules[1].use[0]!/vercel/path0/PalnaduDashboard/node_modules/@ngtools/webpack/src/ivy/index.js!/vercel/path0/PalnaduDashboard/node_modules/css-loader/dist/runtime/api.js");
[15:45:15.399]  8 | /* harmony import */ var _node_modules_css_loader_dist_runtime_api_js__WEBPACK_IMPORTED_MODULE_1___default = /*#__PURE__*/__webpack_require__.n(_node_modules_css_loader_dist_runtime_api_js__WEBPACK_IMPORTED_MODULE_1__);
[15:45:15.399]  9 | // Imports
[15:45:15.400] 10 | 
[15:45:15.400] 11 | 
[15:45:15.400] 12 | var ___CSS_LOADER_EXPORT___ = _node_modules_css_loader_dist_runtime_api_js__WEBPACK_IMPORTED_MODULE_1___default()((_node_modules_css_loader_dist_runtime_noSourceMaps_js__WEBPACK_IMPORTED_MODULE_0___default()));
[15:45:15.400] 13 | ___CSS_LOADER_EXPORT___.push([module.id, "@import url(https://fonts.googleapis.com/css2?family=Noto+Sans+Buhid&family=Roboto+Mono:wght@500&display=swap);"]);
[15:45:15.400] 14 | // Module
[15:45:15.401] 15 | ___CSS_LOADER_EXPORT___.push([module.id, ".w-10 {\n    width: 200px;\n}\n\n.r-30{\n    border-radius: 30%;\n}\n\n.overflow-hidden {\n    height: 100vh;\n    overflow-y: hidden;\n    overflow-x: scroll;\n}\n\n.overflow-scroll {\n    overflow: scroll;\n}\n\n.w-100 {\n    width: 100%;\n}\n\n.r-50 {\n    border-radius: 50%;\n}\n\n.wh-150 {\n    height: 150px;\n    width: 200px;\n}\n\n.center {\n    display: flex;\n    justify-content: center;\n    align-items: center;\n}\n\n.Roboto {\n    font-family: 'Roboto Mono', monospace;\n}\n\n.Noto {\n    font-family: 'Noto Sans Buhid', sans-serif;\n}", ""]);
[15:45:15.401] 16 | // Exports
[15:45:15.401] 17 | /* harmony default export */ const __WEBPACK_DEFAULT_EXPORT__ = (___CSS_LOADER_EXPORT___);
[15:45:15.401] 18 | 
[15:45:15.401] 
[15:45:15.402] 
[15:45:15.443] Error: Command "ng build" exited with 1
