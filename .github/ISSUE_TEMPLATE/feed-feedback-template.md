---
name: Feed feedback template
about: Specific feedback about an element of an existing feed

---

Applying rules:
- Self-describing rule name ( rule issue url ) 

Not like this:

```javascript
  "property": {
    "type": "IncorrectTypeName"
  }
}
```


Like this:

```javascript
  "property": {
    "type": "CorrectTypeName" /* self describing rule name, inserted to indicate application of rule */
  }
```
