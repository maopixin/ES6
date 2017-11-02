```javascript   
//导出
let a = 1,
    b = 2,
    c = 3;
export {//标准导出
    a,b,c
}
export default function(){//默认导出
    console.log(1);
} 


//导入
import s,{a,b,c} from './a2.js';
//默认导出可以修改名称，标准导出不可以改变名字


```