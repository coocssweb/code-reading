<h1 align="center">react-hook-form</h1>
一个React Hooks 表单验证。
https://github.com/react-hook-form/react-hook-form

<h2 align="center">参数</h2>


```js
{
    // 职责: 定义表单验证触发的时机
    // 可取值: onChange | onBlur | onSubmit | onTouched
    mode,               
    // 职责: 定义表单错误重新验证的时机
    // 可取值: onChange | onBlur | onSubmit
    reValidateMode,
    // 职责: 定义其他第三方验证库，如:Yup, Joi等等
    resolver,
    // 职责:
    context,
    defaultValues,
    shouldFocusError,
    // 职责：当书记
    shouldUnregister,
    criteriaMode,
}
```

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
