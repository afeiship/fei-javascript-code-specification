# React相关：
> FB的react是个好东东

## 通用组件：
+ 来源github 或者 npm
+ bower


## 业务组件：
+ 暂时不用React SFC方式定义组件，统一编码用es6 class extends Component 方式：
```jsx
import { $api } from 'services/index';
export default class extends React.Component {
  // static area;
  static displayName = 'my-component';
  static defaultProps = {};

  // properties
  get value(){
    return 123;
  }

  // prototype - contructor
  constructor(inProps){
    super(inProps);
    this.state = {
      value: inProps.value
    }
  }

  componentDidMount() {
  }

  componentWillUnmount() {
  }

  // user actions
  onChange = inEvent => {};

  // view
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
yo react-app:view
yo react-app:service
yo react-app:mixin
```

## 组件名
```js
<div className="my-component" data-component="my-component">
  // ... codes
</div>
```


## 参考：
+ https://github.com/afeiship/generator-react-app
+ https://github.com/baifendian/fe-style-guide/blob/master/React.md
