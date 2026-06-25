#### Diffused

Taming Revocable Spot VM Instances with **Diffused** — a Linux runtime shim that
enables *process diffusion*: seamlessly roaming a program's execution across cloud
spot instances to handle revocation while keeping the spot discount.

Project page: https://guseclab.github.io/diffused/

##### Hosting the project page

The site is a static `index.html` at the root of the `website` branch. To
enable it, go to **Settings → Pages** and set the source to the `website`
branch, `/ (root)` folder. It serves at `guseclab.github.io/diffused/`.
`.nojekyll` disables Jekyll so files are served as-is.
