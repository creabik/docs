---
description: we use the layout types in. section wrap
---

# Sections

there is a lot of sections you can use,  just copy  past the section from the elements page or from any HTML page  you have

```markup
<section class="section is_sm call2action has_style1">
    <div class="container">
        ...
    </div>
</section>
```

{% hint style="warning" %}
for each section is required to use the **`section`** class and the **`is_sm`** _class if you want it to be small or **`is_md`** to be medium or **`is_lg`**_ to be large 
{% endhint %}

{% hint style="danger" %}
for each section is required to use the name of section to be the element inside of it work 

if you weantto use the feautures section  you need to add feautures class to the section   
{% endhint %}

{% tabs %}
{% tab title="with style 1" %}
```markup
<section class="section is_sm feafeatures  has_style1">
    <div class="container">
        ...
    </div>
</section>
```
{% endtab %}

{% tab title="with style 2" %}
```markup
<section class="section is_sm feafeatures  has_style2">
    <div class="container">
        ...
    </div>
</section>
```
{% endtab %}
{% endtabs %}



