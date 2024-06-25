# Polaris Documentation

 This **Polaris proposal tool documentation** uses the mkdocs material theme which in turn requires python to be installed.

You can find detailed theme instructions in the [mkdodcs material site](https://squidfunk.github.io/mkdocs-material/). However, all of the necessary packages can be installed with

```shell
pip install -r requirements.txt
```

## plantuml

Various diagrams are created using [plantuml](https://plantuml.com). The way that this is integrated with markdown is like

    ```plantuml id="myDiag" format="png" classes="uml myDiagram" alt="My super diagram placeholder" title="My super diagram" width="300px" height="300px"
      Goofy ->  MickeyMouse: calls
      Goofy <-- MickeyMouse: responds
    ```


## Running the website locally

Once you've made your working copy of the site repo, from the repo root folder, run:

```bash
mkdocs serve
```

and navigate to http://127.0.0.1:8000/
