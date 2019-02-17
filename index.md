---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Taneční skupina Příbramské Rebelky jsou kamarádky, které rády tančí a baví je užívat si volný čas tancem...láska k hudbě a k tanci je spojuje už od října 2017. Pravidelně trénují u milé paní šenkové Vendulky v hostinci U Pletánků, kde máme svoji základnu. S radostí a nadšením Vám rády zatančí na Vámi pořádané akci či rodinné oslavě

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
 ![image tooltip here]({{ myimage.path }}) 
{% endfor %}
