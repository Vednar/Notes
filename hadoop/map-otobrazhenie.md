# Map \(отображение\)

**Map** - функция и этап в потоке MapReduce, в котором исходные данные преобразуются по какому-то правилу в более удобный для работы формат.

{% tabs %}
{% tab title="Plain Text" %}
```java
//сигнатура класса, реализующего Mapper
Mapper<InpKeyParam, InpValParam, OutKeyParam, OutValParam>
```
{% endtab %}
{% endtabs %}



