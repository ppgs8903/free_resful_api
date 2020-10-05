---
description: 天气api
---

# wheather api

{% api-method method="get" host="https://www.apiopen.top/weatherApi" path="" %}
{% api-method-summary %}

{% endapi-method-summary %}

{% api-method-description %}
天气情况
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="city" type="string" required=true %}
 城市名称
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "code": 200,
    "msg": "成功!",
    "data": {}
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



