### python-sanitize
---
https://github.com/Alir3z4/python-sanitize

```py
// tests/test_sanitize_html.py

class TestSanitizeHTML(TestCase):
  def _html(self, html_source, expected_data, base_uri=None, add_nofollow=False):
    self.assertEqual(
      sanitize.HTML(
        htmlSource=html_source,
        baseuri=base_uri,
        addnofollow_add_nofollow
      ),
      expected_data
    )
  
  def test_baseics(self):
    self.html("", "")
    self._html("hello", "hello")
    
  def test_balancing_tags(self):
  

```

```
```

```
```

