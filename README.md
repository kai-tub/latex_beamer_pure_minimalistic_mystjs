# LaTeX Beamer Pure Minimalistic MySTjs Template (WIP!)

A presentation theme for LaTeX-Beamer that is truly minimalistic, so that the focus is on the presenter and not on the slides.

![](thumbnail.png)

- Author: Kai Norman Clasen
- Author Website: https://github.com/kai-tub/latex-beamer-pure-minimalistic-mystjs
<!-- - [Submission Guidelines](https://github.com/kai-tub/latex-beamer-pure-minimalistic) -->

## Steps to creating your own template!

- [x] ๐ Create this repository. Nailed it. ๐
- [x] ๐ Replace the `template.tex` with your existing LaTeX template/article
- [x] ๐ฏโโ๏ธ Copy in any other style, definitions or images necessary for the template
- [x] ๐ฉโ๐ฌ Add the files necessary into `files` list in the `template.yml` ([documentation](https://js.myst.tools/jtex/template-yml))
- [x] ๐งโโ๏ธ Start replacing template values with `[-options.my_value-]` and put in `[# if parts.abstract #]` conditions to toggle sections on and off ([documentation](https://js.myst.tools/jtex/template-rules))
- [x] ๐ฉ๐ฟโ๐ป Install [jtex](https://js.myst.tools/jtex) (`npm install -g jtex`) and run `jtex check` ([documentation](https://js.myst.tools/jtex/command-line))
- [ ] ๐ช Continue to improve the options in your template for `parts` and `options` ([documentation](https://js.myst.tools/jtex/document))
- [x] ๐พ When ready, save your `template.yml` and run `jtex check --fix`, this will add various packages that are auto detected and fix document options ([documentation](https://js.myst.tools/jtex/command-line))
- [ ] ๐งช Test with real content: `myst build my-document.md --template ../path/to/template` ([documentation](https://js.myst.tools/guide/creating-pdf-documents))
- [x] ๐ธ Create a `thumbnail.png` with an accurate screenshot of the template
- [ ] ๐งญ Update this README, and check all values in the `template.yml`
- [ ] ๐ Push to GitHub, and contribute to the [community templates repository](https://github.com/myst-templates/templates)
