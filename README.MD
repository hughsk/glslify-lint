# glslify-lint
a transform for glslify that used to lint glsl source

## Usage
1. install [glslangValidator](https://www.khronos.org/opengles/sdk/tools/Reference-Compiler/)
2. `npm install glslify-lint`
3. apply transform `glslify-lint` in browserify
  ```bash
  browserify test.js -t [ glslify -p glslify-lint ] > bundle.js
  # or this
  browserify test.js -t [ glslify --post-transform glslify-lint ] > bundle.js
  ```
