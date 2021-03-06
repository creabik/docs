# Change Fonts:

In order to use google fonts, you need to visit [Google Fonts Library](https://fonts.google.com/) and follow the instructions on how to get a new font. After you have decided on the styles of the font that you want to load, or download it in `./assets/fonts/` 

{% hint style="success" %}
after need to add the name you font in **./assets/scss/bases/bases.scss** like this :
{% endhint %}

{% code title="bases.scss" %}
```css
  @font-face {
      font-family: "sora_bold";
      src: url("../fonts/Sora/Sora-VariableFont_wght.ttf") format("truetype");
      font-weight: bold;
  }
                                
  @font-face {
      font-family: "sora";
      src: url("../fonts/SpaceGrotesk-Regular.ttf") format("truetype");
      font-weight: normal;
  } 
```
{% endcode %}

{% hint style="success" %}
Go to .**/assets/scss/1-helpers/\_variables.scss** and edit this file with your new font like that:
{% endhint %}

{% code title="variables.scss" %}
```css

  $font-primary:"sora_bold";
  $font-secondary:"sora";
```
{% endcode %}

