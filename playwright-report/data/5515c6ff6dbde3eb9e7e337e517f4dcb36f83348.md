# Page snapshot

```yaml
- generic [ref=e4]:
  - link "Fork me on GitHub":
    - /url: https://github.com/tourdedave/the-internet
    - img "Fork me on GitHub" [ref=e5] [cursor=pointer]
  - generic [ref=e6]:
    - generic [ref=e7]:
      - heading "Dynamic Controls" [level=4] [ref=e8]
      - paragraph [ref=e9]: This example demonstrates when elements (e.g., checkbox, input field, etc.) are changed asynchronously.
      - heading "Remove/add" [level=4] [ref=e10]
      - generic [ref=e11]:
        - generic [ref=e12]:
          - checkbox [ref=e13]
          - text: A checkbox
        - button "Remove" [ref=e14] [cursor=pointer]
      - separator [ref=e15]
      - heading "Enable/disable" [level=4] [ref=e16]
      - generic [ref=e17]:
        - textbox [disabled] [ref=e18]
        - button "Enable" [ref=e19] [cursor=pointer]
    - generic [ref=e21]:
      - separator [ref=e22]
      - generic [ref=e23]:
        - text: Powered by
        - link "Elemental Selenium" [ref=e24] [cursor=pointer]:
          - /url: http://elementalselenium.com/
```