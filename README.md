### dexy
---
http://www.dexy.it/

https://github.com/freeCodeCamp/devdocs
```
{
  "client": "Acme INC",
  "year": 2013
}


```

```
find .

cd output/
find .

dexy nodes -alias doc

```

```yaml
# dexy.yaml
baz/*.txt:
  - output-name: "%(name)s-file.abc"
bar/baz.txt:
  - output-name: foo-{year}-baz.txt
bar/bell.txt:
  - output-name: "/bell2.txt"
foo.txt:
  - output-name: foo-%(year)s.txt
```

