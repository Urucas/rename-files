# rename-files
Rename files in a directory with regular expressions

#Install 
```bash
npm install -g rename-files
```

# Usage
```bash
rename-files <relative_dir> <pattern> [replace] [--verbose]
```

**API**
```javascript
import rename from 'rename-files'
let [err, list] = rename({dir, pattern, replace[, verbose]});
```
