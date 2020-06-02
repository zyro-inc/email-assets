# email-assets

Logos and other images used in emails or email signatures.

## How to link your image

1. Add your image to repository. 
**Important!** Think of what folder structure you want to have, as you don't want it to change (at least not often), so your images are visible in emails that were sent earlier.

2. Link it with jsdelivr, instructions: `https://www.jsdelivr.com/?docs=gh`

### Example:

```
<img src="https://cdn.jsdelivr.net/gh/zyro-inc/email-assets@master/logos/zyro-64.png" alt="Zyro" width="32" height="32" border="0" nosend="1" />
```

#### Example breakdown:

`https://cdn.jsdelivr.net` 
+ `/gh`
+ `/zyro-inc`
+ `/email-assets` - repository name
+ `@master` - master branch
+ `/logos` - folder / path
+ `zyro-64.png` - filename

You only need to update `path` and `filename` for every image.
