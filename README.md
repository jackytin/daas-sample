# daas-sample


```
<root org="doublechain"
    chinese_name="产品管理系统"
    english_name="银行模拟平台3"
>


    <platform
        name="简单产品管理|产品管理"
        founded="now()"
        contact_number="992887654321"
    />

   
</root>

```


```
<root org="doublechain"
    chinese_name="产品管理系统"
    english_name="银行模拟平台3"
>


    <platform
        name="简单产品管理|产品管理"
        founded="now()"
        contact_number="992887654321"
    />

    <product name="产品" platform="platform()"/>
    <sku name="产品" product="product()" platform="platform()" create_time="createTime()"/>
    <brand name="宝洁|老干妈2" platform="platform()"/>
</root>
```
