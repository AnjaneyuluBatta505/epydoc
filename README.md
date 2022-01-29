# epydoc
python3 support for http://epydoc.sourceforge.net/

It will generate docs with UML diagrams also.

### pre-requisites

- install [graphviz](https://graphviz.org/download/)

### install epydoc

```sh
pip install git+git@github.com:AnjaneyuluBatta505/epydoc.git
```

### generate docs

```she
pydoc -v -o html/api --name my_docs --css white --inheritance listed --graph all  path/to/project --debug
```

For more advanced usage read http://epydoc.sourceforge.net/manual-usage.html 
