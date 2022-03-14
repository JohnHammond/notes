# Biteme

> John Hammond


------------

Trying things with images:

![](Pasted%20image%2020220313221939.png)


And with code blocks:

```python
#!/usr/bin/env python3

import os


text = []
for i in range(1,4464):
	text.append(open(f"source/{i}", "rb").read()[0])

print(bytearray(text).decode("utf-8"))
```

	