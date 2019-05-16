# BEM details

## layouts

| Role       | OOCSS   | BemName     |
| ---------- | ------- | ----------- |
| Navigation | .nav    | .mod-nav    |
| Header     | .hd     | .mod-hd     |
| Body       | .bd     | .mod-bd     |
| Footer     | .ft     | .mod-ft     |
| Left       | .left   | .mod-left   |
| Right      | .right  | .mod-right  |
| Top        | .top    | .mod-top    |
| Middle     | .middle | .mod-middle |
| Bottom     | .bottom | .mod-bottom |

## elements

| Role   | OOCSS  | BemName    |
| ------ | ------ | ---------- |
| Text   | .text  | .mod-text  |
| Label  | .label | .mod-label |
| Button | .btn   | .mod-btn   |


## componenets
> example: nx-dialog

| Role   | OOCSS                     | BemName                      |
| ------ | ------------------------- | ---------------------------- |
| Dialog | .nx-dialog                | .nx-dialog                   |
| Header | .nx-dialog > .hd          | .nx-dialog__header           |
| Close  | .nx-dialog > .hd > .close | .nx-dialog__close            |
| Title  | .nx-dialog > .hd > .label | .mod-label .nx-dialog__title |
| Body   | .nx-dialog > .bd          | .mod-bd .nx-dialog__body     |
| Footer | .nx-dialog > .ft          | .mod-ft .nx-dialog__footer   |


## behaviors (with modifer)
> example: nx-form

| Role   | OOCSS    | BemName           |
| ------ | -------- | ----------------- |
| Action | .create  | .nx-form--create  |
| Action | .update  | .nx-form--update  |
| Action | .destroy | .nx-form--destroy |


## status (with modifer)
> example: nx-alert

| Role    | OOCSS   | BemName           |
| ------- | ------- | ----------------- |
| Success | .pass   | .nx-alert--pass   |
| Failed  | .failed | .nx-alert--failed |


