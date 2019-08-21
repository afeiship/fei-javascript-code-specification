# api
> 一此API的配置约定。

## rest api configuration
> 这是一些通用的约定，其它的情况，可相对自由发挥。

| api     | type         | description                  |
| ------- | ------------ | ---------------------------- |
| list    | 列表         | 一次性取完整的               |
| page    | 分页         | 带分页的，可约定参数         |
| create  | 创建         | 创建逻辑(POST)               |
| update  | 更新/编辑    | 更新/编辑逻辑(POST/PUT)      |
| destroy | 销毁/删除    | 销毁/删除逻辑(POST/DELETE)   |
| desc    | 详情页(简短) | 一些简短的详情(GET/POST)     |
| detail  | 详情页(完整) | 一般指CURD的详情页，参数为ID |

## example
```js
const config = {
  home_picture_list: ['post', '/mpadmin/mp/get_home_pictures'],
  home_picture_destroy: ['post', '/mpadmin/mp/delete_home_picture'],
  home_motto_list: ['post', '/mpadmin/mp/get_home_mottos'],
  home_motto_create: ['post', '/mpadmin/mp/add_home_motto'],
  home_motto_destroy: ['post', '/mpadmin/mp/delete_home_motto']
};
```
