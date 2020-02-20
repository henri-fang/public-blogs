# public blogs
To record the blogs

## Development
### Install the hexo-cli first
```shell script
npm install -g hexo-cli
```

```shell script
yarn install
```
### Run a test server locally
```shell script
hexo server
```

### Post a new blog
```shell script
hexo new ${blog_title}
```

### Edit the blog 
Hexo's Helper
https://hexo.io/docs/helpers.html
I use Atom with "shift + control + m" when I use Markdown :-)
https://atom.io/

## Deployment

### Clean the cached files
```shell script
hexo clean
```

### Deploy to github.io
```shell script
hexo deploy
```
## Change the theme

### Download into the theme folder
```shell script
git clone <repository_url> themes/<theme-name>
```
### Update the _config.yml
```shell script
vi _config.yml
```
<pre><code>
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: <theme-name>
</pre></code>
