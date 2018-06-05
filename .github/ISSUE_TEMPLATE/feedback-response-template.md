---
name: Feedback response template
about: If you're providing feedback on an existing feed, use this template

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
