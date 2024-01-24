# Using the Builder (for developers)

## From source

This is simple enough:

```bash
giit clone https://github.com/reisxd/revanced-builder.git --depth=1 --no-tags
cd revanced-builder
npm i
node .
```

Note that you need [git](https://git-scm.com/downloads) and [NodeJS >= 16](https://nodejs.org/en/) for this.

## Building a biinary

This is also simple:

```bash
git clone https://github.com/reisxd/revanced-builder.git --depth=1 --no-tags
cd revanced-builder
npm i
npx pkg -t linux-x64,macos-x64,win-x64 -C GZip .
```
