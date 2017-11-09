## Introduction
[WooCommerce Product Slider Pro](https://shapedplugin.com/plugin/woocommerce-product-slider-pro/) is an amazing product slider to slide your WooCommerce Products in a tidy and professional way. It allows you to create easily attractive product slider or carousel on your website and increase your sales. You can display product slider in pages, posts, custom template and even sidebar or widget as well as anywhere you want. It comes with built-in advanced Shortcode Generator to easily control the look and function of the product slider.

It has extremely easy-to-use Shortcode Generator back-end interface that can help you to build modern and versatile product slider or carousel that cannot miss in a professional shop.
## Getting Started
##System Requirements##
To get the best experience of this plugin, we recommend the followings–

1. PHP 5.6 or later
2. MySQL 5.6 or later
3. WordPress 4.4.1 or later

To be sure about the above requirements contact your hosting vendor.
## Shotcode

```markdown
[woo-product-slider-pro]
```
Call shortcode to your page template php file using
```markdown
<?php  echo do_shortcode('[woo-product-slider-pro]'); ?>
```
| No. | Attribute | Defaul Value | Options | Description |
| --- | --- | --- | --- | ---| --- |
| 1 | title | Latest Product | text | To show product slider section title, use this attribute.|
| 2 | items | 4 | numeric value only e.g. 5 | Number of columns for the largest view.|
| 3 | items_desktop | 4 | numeric value only e.g. 5 | Number of columns for the desktop view.|
| 4 | items_desktop_small | 3 | numeric value only e.g. 5 | Number of columns for the small destktop view.|
| 5 | items_tablet | 2 | numeric value only e.g. 5 | Number of columns in for the tablet view.|
| 6 | items_mobile | 1 | numeric value only e.g. 5 | Number of columns in for the mobile view.|
| 7 | total_items | 10 | numeric value only e.g. 5 | To show more that 10 products, change total_items value.|
| 8 | color | #e74c3c | color code | Set product slider brand color.|
| 9 | pagination | true | 'true / false' | On / off slider pagination.|


| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |



10	pagination_numbers	true	true / false	Pagination numers on /off.
11	nav	true	true / false	Navigation on / off.
12	auto_play	true	true / false or any number	Autoplay time in millisecond and auto play on / off.
13	stop_on_hover	true	true / false	Stop product slider on hover.
14	products_type	blank	category / feature	Use products type category or feature.
15	rating	true	true / false	Product rating show / hide.
16	sale_text	true	true / false	Product sale text show / hide.
17	category	blank	blank/category name/category1, category2	 For all categories no need to write category name; for single category = category-name; for multiple categories write category names with comma = category1, category2.
18	order_by	date	date / title / modified / author / rand	Select an orderBy option.
19	order	DESC	DESC / ASC	Select an order option.
20	theme	theme_one	theme_one / theme_two	Set product slider theme style.
21	width	400	use any number	Set product image width.
22	height	500	use any number	Set product image height.
23	crop	true	true / false	Set product image crop.
24	slides_to_scroll	1	use any number	Set product per slide.
25	speed	300	use any number	Set slide speed.
26	auto_play_speed	3000	use any number	Set auto play speed.
27	rtl	false	true / false	Set rtl option.
```


## Visual Composer Map

## Conclusion

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ShapedPlugin/WC-Prouduct-Slider-Pro-Doc-v.2-/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
