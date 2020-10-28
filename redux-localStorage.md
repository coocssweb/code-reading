<h1 align="center">redux-localStorage</h1>
一个Redux持久化的中间件
https://github.com/elgerlambert/redux-localstorage

## 目录结构，职责

```bash
    ├──persistState/                       * 主文件，返回middleware闭包方法
    ├──createSlicer/                       * 主文件，返回middleware闭包方法
    ├──getSubset/                          * 
    ├──src/                         * 项目代码目录
    ├──├──app/                      * app实现
    ├──├──├──modules/               * 通用模块
    ├──├──assets/                   * 前端资源文件
    ├──├──layout/                   * 基于Ejs的模板文件
    ├──├──pages/                    * 业务代码目录
    ├──├──utis/                     * 工具类
    ├──├──constant.ts               * 通用常量
    ├──├──interface.ts              * typescript 通用接口文件
```


<h2 align="center">参数</h2>



<h2 align="center">返回</h2>

```js
{
    watch,
    control,
    formState,
    handleSubmit,
    reset,
    clearErrors,
    setError,
    errors,
    trigger,
    setValue,
    getValues,
    register,
    unregister,
}
```
