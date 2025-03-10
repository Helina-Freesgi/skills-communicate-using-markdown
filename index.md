# Github Foundations
## Markdown Language
### Syntax
#### Extended Syntax
##### GH Flavored MD

###### Adding Images
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

###### Adding code
```python
    def resolve(self, *args, **kwargs):
        """Resolve the field."""
        bp = self.get_bp(self.event["asset_ref"])
        if bp:
            return bp.serialize()
```
