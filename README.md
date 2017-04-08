# HexoPathBug
Reproduces https://github.com/hexojs/hexo/issues/2451.

## Step to reproduce

1. Clone the repo.
2. `hexo generate`
3. Enter the public folder, check the text generated from `path` for each of `.html` files. The text is located at `header-title` container.
4. Observe that the generated text doesn't correspond to actual page path.
