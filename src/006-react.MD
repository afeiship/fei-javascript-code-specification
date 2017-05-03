# React相关：

## 通用组件：
+ 来源github 或者 npm
+ bower


## 业务组件：
+ 暂时不用React SFC方式定义组件，统一编码用es6 class extends PureComponent 方式：
```jsx
import  AppBase, {$api} from 'components/scripts/index';
export default class extends React.PureComponent {
  render() {
    return (
      <div className="my-component">
        my-component...
      </div>
    );
  }
}
```

## 脚手架：
+ commands:
```bash
yo react-multipage:component
yo react-multipage:module
yo react-multipage:module-multi
yo react-multipage:service
```


## 参考：
+ https://github.com/afeiship/generator-react-multipage
