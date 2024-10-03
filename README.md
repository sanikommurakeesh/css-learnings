Cascading style sheet 
 Without css we can design styles but when we use that we are gonna lose 
a)style reusability 
B)readability
C)modularity

To overcome this we need to use csscreate a css file (xyz.css) in the folder and in that use (h1,h2,p{ baground-colour: red; } ) here h1,h2,p are the tag names used in html 

To apply this css file we need to use link tag in head file  (<link rel=“stylesheet” href=“./ (name of ur css file.css)” >.        :- this will make u happy the css file in ur html file 

3 ways we can us e
1.in line css (no reusability )
2. Internal css(only page level reusability )
3. External css(we can use for different pages )

Advantages:
Style reuasbility
Readability
Modularity
Portability
Page load faster
Change at one place (global change)

CSS RULES 

RULE NO 1:- nearest style has the highest priority

CSS selector: group of styles

Type of selector :
Tag/element selector
Group tag selector
Class selector (.)
Id selector (#)
group of tag/class/id selector
Attribute selector [ ]
Universal selector *



99 percent we are not gonna use id selector

Class selector :(.rake { code} ) this we should write in css file and when applying in html we need to use class=“rake” attribute for applying that style)

The use of high level line can be use id selector(mostly avoid)

Rule -2 : css selector specificity table
In line
Id slector
Class selector
Tag/element selector



target=“_blank” will take us to new page 

Atribute selector :
I we want to add color to a attribute which contains in several pages then we can use attribute selector

We need to select a attribute which is different from all the we can us e
a[atribut ]{
Bag
}
With this we can differentiate that attribute from other 
