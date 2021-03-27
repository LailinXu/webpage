# Lailin's webpage

## Setup
1. Check out the repository
```
git clone git@github.com:LailinXu/webpage.git .
```

2. Install Hugo

```
brew install hugo
```

See also the quick-start tutorial [here](https://gohugo.io/getting-started/quick-start/).

3. Generate the webpgages for local test

```
hugo server -D
```

## Deploy the website

1. Generate public webpages
```
hugo -D
```
Output will be in `./public/` directory by default (`-d/--destination` flag to change it, or set `publishdir` in the config file).

2. Upload files to your website server

See the instruction [here](https://ustcnet.ustc.edu.cn/2015/0324/c11130a120792/page.htm)

[Filezilla](https://filezilla-project.org/) can be used to upload files to the server.

## Some tips

* Better use lower case for files
