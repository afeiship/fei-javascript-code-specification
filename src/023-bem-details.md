# BEM details
> 自己对 CSS BEM 的理解。

## description
1. Block: 组件名
2. Element: 
   1. 这里可以是 components 名字
   2. 也可以是 role 的名字
3. Modifer: status/action
4.1 标准的状态： `nx-block__elem is-modifer`
4.2 一些行为： `nx-block__elem action-xxx`
4.3 允许扩展：这条待定 (visible-true/false | status-a/n-f)


## 1. layouts
> 一些常用的可复用元素。
| Role       | OOCSS   | BemName     |
| ---------- | ------- | ----------- |
| Navigation | .nav    | .mod-nav    |
| Header     | .hd     | .mod-header |
| Body       | .bd     | .mod-body   |
| Footer     | .ft     | .mod-footer |
| Left       | .left   | .mod-left   |
| Right      | .right  | .mod-right  |
| Top        | .top    | .mod-top    |
| Middle     | .middle | .mod-middle |
| Bottom     | .bottom | .mod-bottom |


## 2. componenets
> example: nx-dialog (原来的data-role/大的区块)。

| Role   | OOCSS                     | BemName            |
| ------ | ------------------------- | ------------------ |
| Dialog | .nx-dialog                | .nx-dialog         |
| Header | .nx-dialog > .hd          | .nx-dialog__header |
| Close  | .nx-dialog > .hd > .close | .nx-dialog__close  |
| Title  | .nx-dialog > .hd > .label | .nx-dialog__title  |
| Body   | .nx-dialog > .bd          | .nx-dialog__body   |
| Footer | .nx-dialog > .ft          | .nx-dialog__footer |


## 3.1 behaviors/actions (with modifer)
> Action 本质是一种状态。(HTTP)

| Role   | OOCSS    | BemName         |
| ------ | -------- | --------------- |
| Add    | .create  | .action-create  |
| Edit   | .update  | .action-update  |
| Delete | .destroy | .action-destroy |


## 3.2 status (with modifer)
> example：真正的 modifer 部分，与 element/component 无关，直接使用 is-

| Role    | OOCSS   | BemName    |
| ------- | ------- | ---------- |
| Success | .pass   | .is-pass   |
| Failed  | .failed | .is-failed |


