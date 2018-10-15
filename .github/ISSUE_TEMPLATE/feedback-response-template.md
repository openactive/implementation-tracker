---
name: Feedback response template
about: If you're providing feedback on an existing feed, use this template

---

## Issue


## Example

Not like this:

```javascript
{
  "@context": "https://openactive.io/",
  "type": "SessionSeries",
  "property": "incorrect"
}
```

Like this:

```javascript
{
  "@context": "https://openactive.io/",
  "type": "SessionSeries",
  "property": "correct" /* self describing rule name, inserted to indicate application of rule */
}
```
