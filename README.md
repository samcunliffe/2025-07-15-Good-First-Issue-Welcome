# UCL talk template with [marp](https://marp.app/)

This is my very minimalist template for UCL talks using [marp](https://marp.app/)/[marpit](https://marpit.marp.app/).  Anyone in UCL is welcome to use the template! If you're not from UCL then please remove the UCL branding. (But at that point, you're just using the default theme!) Anything else (code, infrastructure, etc) is freely reuseable under [MIT-0](./LICENSE.md).

## How to use this template

1. Follow [the instructions for creating a new repository from a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) (**tl; dr** click on "Use this template").

2. Edit [slides.md](./slides.md) to build your talk. 
    - Follow the excellent [marpit](https://marpit.marp.app/image-syntax) docs for inserting images and backgrounds and split screens etc. Put images in the [assets](./assets) folder.
    - I recommend the [marp-vscode extension](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) if you use Visual Studio Code.

3. If you push to GitHub there is a [workflow](.github/workflows/marp.yml) to automatically build the talk with [marp-cli](https://github.com/marp-team/marp-cli) and publish the result to a `gh-pages` branch.
    - Go to the repo settings and enable GitHub pages ([follow from step 5 of these instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)), you should then see your slides at `https://yourusername.github.io/name-of-your-talk-repo`.

 If you're not ready or don't want to publish your talk then don't do the final steps.

## Further reading

* [UCL branding instructions](https://www.ucl.ac.uk/staff/external-engagement/brand-and-visual-identity).
* [UCL banner usage rules](https://www.ucl.ac.uk/brand/brand-essentials/ucl-banner).
