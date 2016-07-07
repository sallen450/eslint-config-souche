# sclint

## Installation

``` bash
$ npm install -g sclint
```

if you use `snpm`, run command:
```
$ snpm install -g sclint
```

### 编辑器配置

#### 1. vim

> 推荐使用 Vundle 管理插件

- 安装插件
	```
	Plugin 'scrooloose/syntastic'
	Plugin 'mtscout6/syntastic-local-eslint.vim'
	```
- 配置 .vimrc
	```
	let g:syntastic_javascript_checkers = ['eslint']
	```

#### 2. sublime text 3

- `cmd` + `shift` + `p`
- 输入 `install package`，回车
- 安装 `SublimeLinter` 插件
- 安装 `SublimeLinter-contrib-eslint` 插件

#### 3. atom

- `cmd` + `,`
- 选择 `package` 一栏
- 安装 `linter` `linter-eslint`
- 取消 `linter-eslint` 配置中 `Use global ESLint installation` 选项

## Usage

```
$ sclint init
```

## TODO

- [ ] sclint-update
- [ ] 支持 .eslintrc remote template(download from repo)
- [ ] 新版本更新提示
- [ ] 优化交互提示
- [ ] 增加测试
- [ ] 增加文档
- [ ] 增加规则示例

## License

[MIT](http://opensource.org/licenses/MIT)
