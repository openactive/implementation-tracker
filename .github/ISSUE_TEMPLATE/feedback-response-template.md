---
name: Feedback response template
about: If you're providing feedback on an existing feed, use this template

---

Applying rules:
- Self-describing rule name ( rule issue url ) 

Not like this:

```javascript
{
  "@context": "https://www.openactive.io/ns/oa.jsonld",
  "type": "Event",
  "property": "incorrect"
}
```

Like this:

```javascript
{
  "@context": "https://www.openactive.io/ns/oa.jsonld",
  "type": "Event",
  "property": "correct" /* self describing rule name, inserted to indicate application of rule */
}
```
