> 用于快速构建一个基于 Docker 的 Flask 项目

- `clone` 后直接码自己的逻辑就行了
- 考虑到这个项目未来可能只是我自己拿来使用，没有搞前后端分离
- 默认使用 Bootstrap 作为前端框架，并且已经做好模板分层
- 无任何第三方依赖
- 默认使用阿里云的 `sources.list` 源
- 默认使用阿里云的 `pip.conf` 源


### usage

```bash
docker build -t panmax/docker-flask .
docker run -d --name docker-flask --restart=always -p 5000:5000 panmax/docker-flask
```