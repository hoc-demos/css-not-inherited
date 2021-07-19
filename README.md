# CSS Not Inherited

Border properties are not inherited.

### span has border set
```css
p {
    border: solid 3px darkcyan;
}

span {
  border: solid 3px darkcyan;
}
```

The `<span>` element has a border property set.
![](https://raw.githubusercontent.com/hoc-demos/images/main/css-not-inherited.png)


### span does not have border set

```css
p {
    border: solid 3px darkcyan;
}

span {
/* border: solid 3px darkcyan; */
}

```
The `<span>` element does not have a border property set. The `<span>` element is not inheriting the border from the parent `<p>` element.

![](https://raw.githubusercontent.com/hoc-demos/images/main/css-not-inherited-2.png)

